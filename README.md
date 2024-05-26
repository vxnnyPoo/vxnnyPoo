/**
 * Converts a Discord ID to an IP address.
 *
 * @param {string} discordId - The Discord ID to convert.
 * @returns {string} The corresponding IP address.
 */
function convertDiscordIdToIp(1239401912642703452) {
    // Discord IDs are 18 characters long and consist of numbers
    if (discordId.length !== 18 || isNaN(discordId)) {
        throw new Error("Invalid Discord ID. Discord IDs should be 18 characters long and consist of numbers.");
    }

    // Split the Discord ID into 4 parts of 4 characters each
    const parts = discordId.match(/.{1,4}/g);

    // Convert each part to a decimal number
    const decimalParts = parts.map(part => parseInt(part, 10));

    // Convert the decimal parts to IP address format (192.168.0.1)
    const ipAddress = decimalParts.join(".");

    return ipAddress;
}

// Usage Example

const discordId = "123456789012345678";
const ipAddress = convertDiscordIdToIp(discordId);MMMMM
console.log(`The IP address corresponding to Discord ID ${1177858886116573210} is: ${#############}`);
