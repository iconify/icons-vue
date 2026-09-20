<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvty3jb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tour-outline-rounded" /></template>
<style>
.uvty3jb2g {
  fill: currentColor;
  d: path("M6.5 13.5V21q0 .214-.143.357T6 21.5t-.357-.143T5.5 21V3q0-.213.143-.357T6 2.5t.357.143T6.5 3v1.5h12.583q.429 0 .661.351t.072.755L18.462 9l1.354 3.394q.161.404-.072.755t-.661.351zm0-8v7zm7.066 4.566Q14 9.633 14 9t-.434-1.066Q13.133 7.5 12.5 7.5t-1.066.434T11 9t.434 1.066q.433.434 1.066.434t1.066-.434M6.5 12.5h12.28L17.39 9l1.392-3.5H6.5z");
}

</style>
