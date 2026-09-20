<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxfa-zben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:steps-sharp" /></template>
<style>
.sxfa-zben {
  fill: currentColor;
  d: path("M18.712 21L7.208 10H2.746L7.99 3.014L10 3.99v3.967l4.002-.971l1.989 6.002L21 17.998L20.25 21zm-5.702 0L1.997 11h4.82l10.43 10z");
}

</style>
