<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnct95bes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:verified-user-sharp" /></template>
<style>
.nnct95bes {
  fill: currentColor;
  d: path("M10.95 15.55L16.6 9.9l-1.425-1.425L10.95 12.7l-2.1-2.1l-1.425 1.425zM12 22q-3.475-.875-5.737-3.988T4 11.1V5l8-3l8 3v6.1q0 3.8-2.262 6.913T12 22");
}

</style>
