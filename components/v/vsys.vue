<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lony26c6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vsys" /></template>
<style>
.lony26c6b {
  fill: var(--svg-color--ff8836, #ff8836);
  d: path("M3.149 4.5h5.155c.03 0 .052 0 .075.023q.038.018.06.055l6.273 10.415a.16.16 0 0 1 0 .18l-2.566 4.248a.16.16 0 0 1-.058.058a.154.154 0 0 1-.212-.058L3.02 4.75a.17.17 0 0 1 0-.164a.16.16 0 0 1 .053-.062a.15.15 0 0 1 .075-.024m10.805 0h6.896c.03 0 .052.008.075.023a.16.16 0 0 1 .052.063q.022.035.023.077c0 .039 0 .063-.023.086l-3.443 5.723a.16.16 0 0 1-.136.078a.15.15 0 0 1-.135-.079L13.811 4.75a.17.17 0 0 1 .056-.223a.2.2 0 0 1 .08-.026z");
}

</style>
