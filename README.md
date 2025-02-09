# .bashrc
apt update
apt install neofetch
apt upgrade
sudo nano .bashrc



add to the end of file
copy and add it to the end of the file .bashrc
########################

neofetch
# Function to get local IP
echo "find your ip"
get_local_ip() {
    local_ip=$(hostname -I | awk '{print $1}')
    echo "Local IP: $local_ip"
}

# Function to get WAN IP
get_wan_ip() {
    wan_ip=$(curl -s ifconfig.me)
    echo "WAN IP: $wan_ip"
}

# Display the IPs
get_local_ip
get_wan_ip

fi
#########################

