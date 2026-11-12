<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bwdd5rb7e"/><path class="d_-sftbvq"/><path class="evib1nbfc"/><path class="iurcs7brt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:widget-3-broken" /></template>
<style>
.bwdd5rb7e {
  d: path("M17.5 10.5C19.7091 10.5 21.5 8.70914 21.5 6.5C21.5 4.29086 19.7091 2.5 17.5 2.5C15.2909 2.5 13.5 4.29086 13.5 6.5C13.5 8.70914 15.2909 10.5 17.5 10.5Z");
}

.d_-sftbvq {
  d: path("M6.5 21.5C8.70914 21.5 10.5 19.7091 10.5 17.5C10.5 15.2909 8.70914 13.5 6.5 13.5C4.29086 13.5 2.5 15.2909 2.5 17.5C2.5 19.7091 4.29086 21.5 6.5 21.5Z");
}

.evib1nbfc {
  d: path("M2.66789 5.34961C2.55868 5.71394 2.5 6.10012 2.5 6.5C2.5 8.70914 4.29086 10.5 6.5 10.5C8.70914 10.5 10.5 8.70914 10.5 6.5C10.5 4.29086 8.70914 2.5 6.5 2.5C6.10012 2.5 5.71394 2.55868 5.34961 2.66789");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iurcs7brt {
  d: path("M21.8321 19.1504C21.9413 18.7861 22 18.3999 22 18C22 15.7909 20.2091 14 18 14C15.7909 14 14 15.7909 14 18C14 20.2091 15.7909 22 18 22C18.3999 22 18.7861 21.9413 19.1504 21.8321");
}

</style>
