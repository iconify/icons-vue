<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u9ct9obbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mention-16-regular" /></template>
<style>
.u9ct9obbt {
  fill: currentColor;
  d: path("M8 1a7 7 0 0 1 7 7c0 2.133-1.1 3.5-2.5 3.5c-.885 0-1.65-.547-2.093-1.488c-.581.892-1.54 1.488-2.657 1.488C5.915 11.5 4.5 9.891 4.5 8s1.415-3.5 3.25-3.5c.885 0 1.672.375 2.25.975V5a.5.5 0 0 1 1 0v3c0 1.867.9 2.5 1.5 2.5S14 9.867 14 8a6 6 0 1 0-3.747 5.562a.54.54 0 0 1 .59.109c.243.243.183.652-.134.785A7 7 0 1 1 8 1m-.25 4.5C6.547 5.5 5.5 6.577 5.5 8s1.047 2.5 2.25 2.5S10 9.423 10 8S8.953 5.5 7.75 5.5");
}

</style>
