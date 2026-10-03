<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cmlvnu2ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:save-sharp-fill" /></template>
<style>
.cmlvnu2ks {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 2L17 2C17.2652 2 17.5196 2.1054 17.7071 2.2929L21.7071 6.2929C21.8946 6.4804 22 6.7348 22 7L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2ZM7 4L7 7L13 7L13 4L7 4ZM15 14C15 12.3431 13.6569 11 12 11C10.3431 11 9 12.3431 9 14C9 15.6569 10.3431 17 12 17C13.6569 17 15 15.6569 15 14Z");
}

</style>
