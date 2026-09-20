<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r67umuoar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mention-32-regular" /></template>
<style>
.r67umuoar {
  fill: currentColor;
  d: path("M16 2c7.732 0 14 6.268 14 14l-.002.013C29.994 20.272 27.796 23 24.999 23c-1.77 0-3.298-1.093-4.184-2.975C19.65 21.81 17.731 23 15.5 23C11.83 23 9 19.782 9 16s2.83-7 6.5-7c1.77 0 3.344.75 4.5 1.95V10a1 1 0 1 1 2 0v6c0 3.733 1.8 5 2.999 5s3-1.267 3-5v-.017C27.99 9.363 22.622 4 16 4C9.373 4 4 9.373 4 16s5.373 12 12 12c1.236 0 2.428-.189 3.55-.536c.387-.12.814-.03 1.1.257c.513.513.35 1.379-.34 1.602c-1.357.44-2.806.677-4.31.677c-7.732 0-14-6.268-14-14S8.268 2 16 2m-.5 9c-2.405 0-4.5 2.155-4.5 5s2.095 5 4.5 5s4.5-2.155 4.5-5s-2.095-5-4.5-5");
}

</style>
