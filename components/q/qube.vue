<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kg1sdbcvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:qube" /></template>
<style>
.kg1sdbcvx {
  fill: var(--svg-color--0057ff, #0057ff);
  d: path("M19.941 7.362v6.004l-2.647-1.53V9.109L12 6.176L6.706 8.998v5.729L12 17.559l3.97-2.118l3.971 2.118V21l-3.97-2.118L12 21l-7.942-4.362V7.362L12 3z");
}

</style>
