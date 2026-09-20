<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twmi7nbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:variables-sharp" /></template>
<style>
.twmi7nbnm {
  fill: currentColor;
  d: path("M3 17V7h18v10z");
}

</style>
