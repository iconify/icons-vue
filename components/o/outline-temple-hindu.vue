<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9o54ubix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-temple-hindu" /></template>
<style>
.h9o54ubix {
  fill: currentColor;
  d: path("M20 11v2h-2L15 3V1h-2v2h-2.03V1h-2v2.12L6 13H4v-2H2v11h9v-5h2v5h9V11zm-4.69 0H8.69l.6-2h5.42zm-1.2-4H9.89l.6-2h3.02zM20 20h-5v-5H9v5H4v-5h3.49l.6-2h7.82l.6 2H20z");
}

</style>
