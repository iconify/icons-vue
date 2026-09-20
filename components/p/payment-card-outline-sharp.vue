<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwabcdchs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:payment-card-outline-sharp" /></template>
<style>
.zwabcdchs {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h16V6H4zm1-1h10L10 7H5zm8-8h6V7h-6zm-9 9V6z");
}

</style>
