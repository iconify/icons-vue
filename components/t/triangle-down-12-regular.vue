<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="s4-cv-boo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:triangle-down-12-regular" /></template>
<style>
.s4-cv-boo {
  fill: currentColor;
  d: path("M6.786 10.541a.903.903 0 0 1-1.572 0L1.122 3.372C.774 2.762 1.211 2 1.91 2h8.182c.698 0 1.135.762.787 1.372zM6 9.881l3.917-6.864H2.083z");
}

</style>
