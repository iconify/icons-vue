<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uscmo6r8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:reply-outline-sharp" /></template>
<style>
.uscmo6r8p {
  fill: currentColor;
  d: path("M19 19v-4q0-1.25-.875-2.125T16 12H6.825l3.6 3.6L9 17l-6-6l6-6l1.425 1.4l-3.6 3.6H16q2.075 0 3.538 1.463T21 15v4z");
}

</style>
