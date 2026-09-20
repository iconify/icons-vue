<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_2u76vfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:newsmode-sharp" /></template>
<style>
.r_2u76vfc {
  fill: currentColor;
  d: path("M3 20V4h18v16zm3.77-3.77h10.46v-1H6.77zm0-3.73h3.384V7.77H6.769zm5.769 0h4.692v-1h-4.693zm0-3.73h4.692v-1h-4.693z");
}

</style>
