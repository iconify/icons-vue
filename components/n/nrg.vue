<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ed6glpbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nrg" /></template>
<style>
.ed6glpbqs {
  fill: var(--svg-color--0bc98d, #0bc98d);
  d: path("M17.4 8.383L12 13.918L10.043 12l3.397-3.476L12 7.005l-5.288 5.158L12 17.3l7.2-7.099L21 12l-9 9l-9-9l9-9z");
}

</style>
