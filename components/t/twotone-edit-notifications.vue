<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4wde1bmr"/><path class="yzp_eu--e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-edit-notifications" /></template>
<style>
.r4wde1bmr {
  fill: currentColor;
  d: path("m16 14.2l-.8.8h-4.6v-4.6l3.68-3.68A3.9 3.9 0 0 0 12 6c-2.21 0-4 1.79-4 4v7h8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.yzp_eu--e {
  fill: currentColor;
  d: path("m17.58 6.25l1.77 1.77L14.37 13H12.6v-1.77zm3.27-.44l-1.06-1.06c-.2-.2-.51-.2-.71 0l-.85.85L20 7.37l.85-.85c.2-.2.2-.52 0-.71M18 12.2V17h2v2H4v-2h2v-7c0-2.79 1.91-5.14 4.5-5.8v-.7c0-.83.67-1.5 1.5-1.5s1.5.67 1.5 1.5v.7c.82.21 1.57.59 2.21 1.09l-1.43 1.43A3.9 3.9 0 0 0 12 6c-2.21 0-4 1.79-4 4v7h8v-2.8zM10 20h4c0 1.1-.9 2-2 2s-2-.9-2-2");
}

</style>
