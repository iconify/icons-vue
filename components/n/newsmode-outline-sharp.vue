<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu3pfebwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:newsmode-outline-sharp" /></template>
<style>
.gu3pfebwp {
  fill: currentColor;
  d: path("M3 20V4h18v16zm1-1h16V5H4zm2.77-2.77h10.46v-1H6.77zm0-3.73h3.384V7.77H6.769zm5.769 0h4.692v-1h-4.693zm0-3.73h4.692v-1h-4.693zM4 19V5z");
}

</style>
