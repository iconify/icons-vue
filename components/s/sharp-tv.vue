<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4g54lbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-tv" /></template>
<style>
.a4g54lbma {
  fill: currentColor;
  d: path("M23 3H1v16h7v2h8v-2h6.99zm-2 14H3V5h18z");
}

</style>
