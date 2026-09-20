<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl4g8enhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:phishing-outline-sharp" /></template>
<style>
.wl4g8enhv {
  fill: currentColor;
  d: path("M6.75 19.25Q5 17.5 5 15V9l5 5l-1.4 1.425l-1.6-1.6V15q0 1.65 1.175 2.825T11 19t2.825-1.175T15 15v-3.175q-.9-.35-1.45-1.112T13 9t.55-1.713T15 6.176V2h2v4.175q.9.35 1.45 1.113T19 9t-.55 1.725t-1.45 1.1V15q0 2.5-1.75 4.25T11 21t-4.25-1.75m9.963-9.537Q17 9.425 17 9t-.288-.712T16 8t-.712.288T15 9t.288.713T16 10t.713-.288M16 9");
}

</style>
