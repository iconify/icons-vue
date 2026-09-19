<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0w-m072b"/><path class="axkayxbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-volcano" /></template>
<style>
.axkayxbng {
  fill: currentColor;
  d: path("M18 8h-7l-2 5H6l-4 9h20zM7.3 15h3.05l.5-1.26l1.5-3.74h4.14l2.86 10H5.08zM13 1h2v4h-2zm3.121 4.468L18.95 2.64l1.414 1.414l-2.829 2.828zM7.64 4.05l1.414-1.414l2.828 2.828l-1.414 1.415z");
}

.s0w-m072b {
  fill: currentColor;
  d: path("M16.49 10h-4.14l-1.49 3.74l-.51 1.26H7.3l-2.22 5h14.27z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
