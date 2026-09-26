<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jtdqffbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:map-pin-sharp-fill" /></template>
<style>
.jtdqffbto {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.7081 16L12.7454 22.6667C12.3478 23.1111 11.6522 23.1111 11.2546 22.6667L5.2918 16C3.857 14.3958 3 12.1523 3 10C3 5.1675 7.1675 1 12 1C16.8325 1 21 5.1675 21 10C21 12.1523 20.143 14.3958 18.7081 16ZM15 10C15 11.6569 13.6569 13 12 13C10.3431 13 9 11.6569 9 10C9 8.3431 10.3431 7 12 7C13.6569 7 15 8.3431 15 10Z");
}

</style>
