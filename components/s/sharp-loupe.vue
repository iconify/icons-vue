<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="feou-eb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-loupe" /></template>
<style>
.feou-eb3m {
  fill: currentColor;
  d: path("M13 7h-2v4H7v2h4v4h2v-4h4v-2h-4zm-.27-4.97c-6.08-.44-11.14 4.62-10.7 10.7c.38 5.28 5 9.27 10.29 9.27H22v-9.68c0-5.3-3.98-9.91-9.27-10.29M12 20c-4.41 0-8-3.59-8-8s3.59-8 8-8s8 3.59 8 8s-3.59 8-8 8");
}

</style>
