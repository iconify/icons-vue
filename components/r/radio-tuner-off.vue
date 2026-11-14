<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="msqh2bonh"/><path class="fe1szwbtl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:radio-tuner-off" /></template>
<style>
.fe1szwbtl {
  d: path("M18.326 14.417q.174-.442.174-.917q0-.123-.012-.245t-.036-.243q-.024-.12-.06-.238t-.082-.231t-.105-.221t-.126-.211q-.069-.102-.146-.197q-.078-.095-.165-.182t-.182-.165t-.197-.146t-.211-.126t-.221-.105q-.114-.047-.231-.082t-.238-.06q-.121-.024-.243-.036T16 11q-.457 0-.884.162M6.75 10.7v4.8m2.75-2v2m-6-12l17 17");
}

.msqh2bonh {
  d: path("M9.4 5.5h12.1v12.1m-6.9.9H2.5V6.4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
