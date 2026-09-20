<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwp-kcbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:note-stack-outline" /></template>
<style>
.hwp-kcbze {
  fill: currentColor;
  d: path("M7 20V8.975q0-.825.6-1.4T9.025 7H20q.825 0 1.413.587T22 9v8l-5 5H9q-.825 0-1.412-.587T7 20M2.025 6.25q-.15-.825.325-1.487t1.3-.813L14.5 2.025q.825-.15 1.488.325t.812 1.3L17.05 5H15l-.175-1L4 5.925l1 5.65v6.975q-.4-.225-.687-.6t-.363-.85zM9 9v11h7v-4h4V9zm5.5 5.5");
}

</style>
