<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k1kyi0yyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rocket-16-filled" /></template>
<style>
.k1kyi0yyi {
  fill: currentColor;
  d: path("M5.146 12.647a.5.5 0 0 1 .708.707l-1 1a.5.5 0 0 1-.708-.707zm-1.5-1a.5.5 0 0 1 .708.707l-1.5 1.5a.5.5 0 1 1-.708-.707zM12.5 1A2.5 2.5 0 0 1 15 3.5v.429c0 1.458-.58 2.858-1.611 3.89l-.511.51a2.5 2.5 0 0 1-.439 2.94l-1.085 1.085a.5.5 0 0 1-.707 0l-.945-.944a1.5 1.5 0 0 1-1.763-.264l-.362-.362l-.661.993a.502.502 0 0 1-.77.077l-2-2a.5.5 0 0 1 .077-.77l.992-.662l-.361-.361a1.5 1.5 0 0 1-.265-1.764l-.943-.943a.5.5 0 0 1 0-.707l1.086-1.085a2.5 2.5 0 0 1 2.939-.44l.51-.51A5.5 5.5 0 0 1 12.072 1zm-9.854 9.147a.5.5 0 1 1 .708.707l-1 1a.5.5 0 1 1-.708-.707zM12.071 2A4.5 4.5 0 0 0 8.89 3.318L5.56 6.646a.5.5 0 0 0 0 .708l3.085 3.086a.5.5 0 0 0 .708 0l3.328-3.329A4.5 4.5 0 0 0 14 3.93V3.5A1.5 1.5 0 0 0 12.5 2zM10 4.25a1.75 1.75 0 1 1 0 3.5a1.75 1.75 0 0 1 0-3.5m0 1a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5");
}

</style>
