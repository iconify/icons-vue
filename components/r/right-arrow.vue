<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="trcllmbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:right-arrow" /></template>
<style>
.trcllmbdv {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M108.58 64L62.47 97.81V76.72H19.42V51.49h43.04v-21.3z");
}

</style>
