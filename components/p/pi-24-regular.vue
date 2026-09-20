<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7aatw13s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pi-24-regular" /></template>
<style>
.d7aatw13s {
  fill: currentColor;
  d: path("M2.5 6.75A2.75 2.75 0 0 1 5.25 4h15a.75.75 0 0 1 0 1.5H17v11.453a1.75 1.75 0 0 0 2.339 1.648l.159-.057a.75.75 0 0 1 .504 1.412l-.159.057c-2.116.756-4.343-.813-4.343-3.06V5.5H9.494a69 69 0 0 1-.247 4.534c-.252 2.862-.758 6.499-1.789 9.462a.75.75 0 0 1-1.416-.492c.969-2.786 1.462-6.275 1.71-9.1A68 68 0 0 0 7.995 5.5H5.25C4.56 5.5 4 6.06 4 6.75v.5a.75.75 0 0 1-1.5 0z");
}

</style>
