<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7duakv3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:unsubscribe-outline" /></template>
<style>
.s7duakv3p {
  fill: currentColor;
  d: path("M12 13L4 8v10h8q0 .525.075 1.013T12.3 20H4q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v5.7q-.45-.225-.962-.375T20 11.1V8zm0-2l8-5H4zm3.463 10.538Q14 20.075 14 18t1.463-3.537T19 13t3.538 1.463T24 18t-1.463 3.538T19 23t-3.537-1.463M16 18.5h6v-1h-6zM4 18V6z");
}

</style>
