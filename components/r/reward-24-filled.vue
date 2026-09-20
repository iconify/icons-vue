<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="of_2sk35h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:reward-24-filled" /></template>
<style>
.of_2sk35h {
  fill: currentColor;
  d: path("M20.25 1.999c.966 0 1.75.784 1.75 1.75v3.043a2.75 2.75 0 0 1-1.477 2.437l-6.3 3.29A5 5 0 0 1 12 22a5 5 0 0 1-2.223-9.48l-6.3-3.29A2.75 2.75 0 0 1 2 6.792V3.749c0-.966.784-1.75 1.75-1.75zM12 13.499a3.5 3.5 0 1 0 0 7a3.5 3.5 0 0 0 0-7m4-10H7.997v6.398l3.887 2.03a.25.25 0 0 0 .232 0L16 9.899z");
}

</style>
