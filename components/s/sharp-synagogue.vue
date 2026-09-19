<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_tkdrbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-synagogue" /></template>
<style>
.e_tkdrbvs {
  fill: currentColor;
  d: path("M6 8v13h4v-7h4v7h4V8l-6-5zm7.5 2c0 .83-.67 1.5-1.5 1.5s-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5s1.5.67 1.5 1.5M3 5c-1.1 0-2 .9-2 2v1h4V7c0-1.1-.9-2-2-2M1 9h4v12H1zm20-4c-1.1 0-2 .9-2 2v1h4V7c0-1.1-.9-2-2-2m-2 4h4v12h-4z");
}

</style>
