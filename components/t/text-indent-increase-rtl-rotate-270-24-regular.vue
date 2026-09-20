<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj67v-bgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-indent-increase-rtl-rotate-270-24-regular" /></template>
<style>
.gj67v-bgv {
  fill: currentColor;
  d: path("M16 17.75a.75.75 0 0 0 1.5 0v-9a.75.75 0 0 0-1.5 0zM9.22 2.72a.75.75 0 0 0-.073.976l.073.084l2 2a.75.75 0 0 0 .976.073l.084-.073l2-2a.75.75 0 0 0-.976-1.133l-.084.073l-1.47 1.47l-1.47-1.47a.75.75 0 0 0-1.06 0M11 20.75a.75.75 0 0 0 1.5 0v-12a.75.75 0 0 0-1.5 0zm-5-3a.75.75 0 0 0 1.5 0v-9a.75.75 0 0 0-1.5 0z");
}

</style>
