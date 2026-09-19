<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjd9mtu1y"/><path class="s9f_3ybiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-rate-review" /></template>
<style>
.rjd9mtu1y {
  fill: currentColor;
  d: path("m4 17.17l.59-.59l.58-.58H20V4H4zM18 14h-7.5l2-2H18zM6 11.53l5.88-5.88c.2-.2.51-.2.71 0l1.77 1.77c.2.2.2.51 0 .71L8.47 14H6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.s9f_3ybiy {
  fill: currentColor;
  d: path("M20 2H4c-1.1 0-1.99.9-1.99 2L2 22l4-4h14c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m0 14H5.17l-.59.59l-.58.58V4h16zm-9.5-2H18v-2h-5.5zm3.86-5.87c.2-.2.2-.51 0-.71l-1.77-1.77c-.2-.2-.51-.2-.71 0L6 11.53V14h2.47z");
}

</style>
