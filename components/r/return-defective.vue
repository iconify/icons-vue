<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bmza8dbpj"/><path class="dttr_gb8r"/><path class="e1uk0pbui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:return-defective" /></template>
<style>
.bmza8dbpj {
  d: path("M15.2 16.5H2.5v-13h19v13h-.7m-8.8 0v4m-4 0h7.2");
}

.dttr_gb8r {
  d: path("M15.5 11.7V11q0-.123-.012-.245t-.036-.243q-.024-.12-.06-.238t-.082-.231q-.047-.113-.105-.221q-.058-.109-.126-.211q-.069-.102-.146-.197q-.078-.095-.165-.182t-.182-.165t-.197-.146t-.211-.126t-.221-.105q-.114-.047-.231-.082t-.238-.06q-.121-.024-.243-.036T13 8.5H8.5");
}

.e1uk0pbui {
  d: path("m10.5 6.5l-2 2l2 2m7.5 4V18m0 3h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
