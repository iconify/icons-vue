<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0ao5qb3m"/><path class="fd_8_2szr"/><path class="ptiy6tbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-cancel-schedule-send" /></template>
<style>
.fd_8_2szr {
  fill: currentColor;
  d: path("M16.5 9c-.42 0-.83.04-1.24.11L1.01 3L1 10l10.06 1.34c-.42.44-.78.93-1.09 1.46L1 14l.01 7l8.07-3.46C9.59 21.19 12.71 24 16.5 24c4.14 0 7.5-3.36 7.5-7.5S20.64 9 16.5 9M3 8.25l.01-2.22l7.51 3.22zm6.1 7.11L3 17.97v-2.22l6.17-.82c-.03.14-.05.28-.07.43M16.5 22c-3.03 0-5.5-2.47-5.5-5.5s2.47-5.5 5.5-5.5s5.5 2.47 5.5 5.5s-2.47 5.5-5.5 5.5");
}

.ptiy6tbup {
  fill: currentColor;
  d: path("m18.27 14.03l-1.77 1.76l-1.77-1.76l-.7.7l1.76 1.77l-1.76 1.77l.7.7l1.77-1.76l1.77 1.76l.7-.7l-1.76-1.77l1.76-1.77z");
}

.y0ao5qb3m {
  fill: currentColor;
  d: path("m3 17.97l6.1-2.61c.02-.14.04-.29.07-.43L3 15.75zM16.5 11c-3.03 0-5.5 2.47-5.5 5.5s2.47 5.5 5.5 5.5s5.5-2.47 5.5-5.5s-2.47-5.5-5.5-5.5m2.47 7.27l-.71.71l-1.77-1.77l-1.77 1.77l-.71-.71l1.77-1.77l-1.77-1.77l.71-.71l1.77 1.77l1.77-1.77l.71.71l-1.77 1.77zM3 8.25l7.52 1l-7.51-3.22z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
