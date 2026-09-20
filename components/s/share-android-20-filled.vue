<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vr3uk3bxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:share-android-20-filled" /></template>
<style>
.vr3uk3bxq {
  fill: currentColor;
  d: path("M17 5.5a2.5 2.5 0 0 1-4.467 1.543L7.915 9.352a2.5 2.5 0 0 1 0 1.297l4.618 2.308a2.5 2.5 0 1 1-.448.894l-4.618-2.308a2.5 2.5 0 1 1 0-3.085l4.618-2.31A2.504 2.504 0 0 1 14.5 3A2.5 2.5 0 0 1 17 5.5");
}

</style>
