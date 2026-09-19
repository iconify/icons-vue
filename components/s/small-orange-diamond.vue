<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="rjvq8qjat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:small-orange-diamond" /></template>
<style>
.rjvq8qjat {
  fill: var(--svg-color--f27a52, #f27a52);
  d: path("m16.019 32l15.98-15.981l15.98 15.98L32 47.98z");
}

</style>
