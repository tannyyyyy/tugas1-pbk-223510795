<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Data Diri</template>

    Saya
    <a href="https://vuejs.org/" target="_blank" rel="noopener">Rifki Nul Arif</a>
    <ul>
      <li>Tanggal Lahir : 04 - 09 - 2002</li>
      <li>Alamat : Kuantan Singingi</li>
      <li>Agama : Islam</li>

      Panggil aja saya Rifki
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Hobi</template>
    <ul>
      <li>Membaca</li>
      <li>Menulis</li>
      <li>Menggambar</li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Skil</template>
    <ul>
      <li>Balap Motor</li>
      <li>Mancing</li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Pendidikan</template>
    <ul>
      <li>TK Islam</li>
      <li>SDN 019 Sungai Jering</li>
      <li>SMP N 6 Teluk Kuantan</li>
      <li>SMA N 1 Teluk Kuantan</li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Media Sosial</template>
    <ul>
      <li>Ig : rifkiariff</li>
    </ul>
  </WelcomeItem>
</template>
