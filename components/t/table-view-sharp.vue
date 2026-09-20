<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unrtt1bfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:table-view-sharp" /></template>
<style>
.unrtt1bfk {
  fill: currentColor;
  d: path("M6 22h7v-4H6zm9 0h7v-4h-7zM2 18V2h16v2H4v14zm4-2h7v-4H6zm9 0h7v-4h-7zm-9-6h16V6H6z");
}

</style>
