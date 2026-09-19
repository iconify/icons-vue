<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6zcc4bpf"/><path class="zf9zfkbpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-font-download" /></template>
<style>
.a6zcc4bpf {
  fill: currentColor;
  d: path("M4 20h16V4H4zm7.07-14.5h1.86l5.11 13h-2.09l-1.14-3H9.17l-1.12 3H5.96zM12 7.98L9.93 13.5h4.14z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.zf9zfkbpm {
  fill: currentColor;
  d: path("M9.17 15.5h5.64l1.14 3h2.09l-5.11-13h-1.86l-5.11 13h2.09zM12 7.98l2.07 5.52H9.93zM20 2H4c-1.1 0-2 .9-2 2v16c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m0 18H4V4h16z");
}

</style>
