<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dmwx0j3ve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vip-20-regular" /></template>
<style>
.dmwx0j3ve {
  fill: currentColor;
  d: path("M15 4a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3zM5 5a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V7a2 2 0 0 0-2-2zm3.028 2.335a.5.5 0 1 1 .944.33L7.305 12.43a.853.853 0 0 1-1.61 0L4.028 7.665a.5.5 0 1 1 .944-.33L6.5 11.699zM10.5 7a.5.5 0 0 1 .5.5v5a.5.5 0 0 1-1 0v-5a.5.5 0 0 1 .5-.5M14 7a2 2 0 1 1 0 4h-1v1.5a.5.5 0 0 1-1 0v-5a.5.5 0 0 1 .5-.5zm-1 3h1a1 1 0 1 0 0-2h-1z");
}

</style>
