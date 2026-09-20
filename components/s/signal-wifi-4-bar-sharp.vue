<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnp7zrbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:signal-wifi-4-bar-sharp" /></template>
<style>
.lnp7zrbda {
  fill: currentColor;
  d: path("M12 21L0 9q2.375-2.425 5.488-3.713T12 4t6.513 1.288T24 9z");
}

</style>
