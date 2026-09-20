<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="s13dpkvet"/><path class="pfmx79bxr"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:t-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pfmx79bxr {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 6.947h-5.474v1.684H20zm-8.842 1.684H9.474v1.685h1.684zm-1.684 8.422h1.684V12H9.474zm3.368-8.422v1.685h1.684V8.63zm0 8.422h1.684V12h-1.684zm0-10.106h-1.684v1.684h1.684zM4 6.947v1.684h5.474V6.947zM20 12v-1.684h-5.474V12zm-8.842-1.684V12h1.684v-1.684zm-7.158 0V12h5.474v-1.684z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.s13dpkvet {
  fill: var(--svg-color--7d00fe, #7d00fe);
  d: path("M24 0H0v24h24z");
}

</style>
