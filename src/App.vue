<script setup lang="ts">
import FlagIcon from '@/index'
</script>

<template>
  <FlagIcon code="gr" />
  <FlagIcon code="gb" :size="25" square />
  <FlagIcon code="us" size="32" circle />
  <FlagIcon code="fr" title="A flag icon" />
  <FlagIcon code="es" :title="(country) => `Country: ${country}`" />
</template>
