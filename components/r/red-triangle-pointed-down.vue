<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="s60d7nb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:red-triangle-pointed-down" /></template>
<style>
.s60d7nb_c {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M32 62L62 2H2z");
}

</style>
