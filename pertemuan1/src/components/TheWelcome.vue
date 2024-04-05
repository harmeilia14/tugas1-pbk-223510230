<script setup lang="ts">
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
    <h2><i>Pendidikan</i></h2>
        SDN 79 Pekanbaru 2010 - 15 <br>
        SMPN 34 Pekanbaru 2016 - 2018 <br>
        SMK Labor Pekanbaru 2019 - 2021 <br>
        Universitas Islam Riau 2022 - Sekarang
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <h2><i>Skill</i></h2>
      Power Point <br>
      PHP <br>
      C++ <br>
      Database
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <h2><i>Pengalaman</i></h2>
      Melakukan Praktik Kerja lapangan di KLT Badan Standarisasi Nasional
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <h2><i>Kontak</i></h2>
      <a href="https://www.instagram.com/harmeiliareski/" target="_blank" rel="noopener">Instagram</a> <br>
      <a href="https://wa.me/qr/V7BOA7SLLNZZC1" target="_blank" rel="noopener">WhatsApp</a>
  </WelcomeItem>
</template>
