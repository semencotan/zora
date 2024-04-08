# zora
class ZoraNFT:
    def __init__(self, name, creator, description, image_url, edition_size, current_price):
        self.name = name
        self.creator = creator
        self.description = description
        self.image_url = image_url
        self.edition_size = edition_size
        self.current_price = current_price

    def display_info(self):
        print("Zora NFT Information:")
        print(f"Name: {self.name}")
        print(f"Creator: {self.creator}")
        print(f"Description: {self.description}")
        print(f"Image URL: {self.image_url}")
        print(f"Edition Size: {self.edition_size}")
        print(f"Current Price: {self.current_price} ETH")

# Example usage
if __name__ == "__main__":
    # Creating an instance of the ZoraNFT class
    my_nft = ZoraNFT(
        name="Digital Artwork",
        creator="ArtistXYZ",
        description="A unique digital artwork minted on Zora.",
        image_url="https://example.com/digital-artwork.png",
        edition_size=10,
        current_price=1.5
    )

    # Displaying information about the Zora NFT
    my_nft.display_info()
