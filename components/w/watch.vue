<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="h85ceub6y"/><path class="lgnwupbaj"/><path class="osb259-pf"/><g class="mrjy-p0fq"><path class="b9ft8_bhf"/><path class="jgw_15_ii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:watch" /></template>
<style>
.b9ft8_bhf {
  d: path("M33.441 31.995c0 1.19-.945 2.153-2.114 2.153c-1.168 0-2.116-.963-2.116-2.153V21.871c0-1.19.947-2.153 2.116-2.153s2.114.962 2.114 2.153z");
}

.h85ceub6y {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M42.487 18.225c0 1.768-4.994 3.198-11.162 3.198c-6.166 0-11.159-1.43-11.159-3.198V3.195c0-1.764 4.993-3.194 11.159-3.194c6.168 0 11.162 1.43 11.162 3.194zm0 42.662c0 1.765-4.994 3.194-11.162 3.194c-6.166 0-11.159-1.43-11.159-3.194v-15.03c0-1.768 4.993-3.197 11.159-3.197c6.168 0 11.162 1.43 11.162 3.197z");
}

.jgw_15_ii {
  d: path("M31.453 34.15c-1.24 0-2.242-.656-2.242-1.462c0-.809 1-1.465 2.242-1.465h10.554c1.24 0 2.243.656 2.243 1.465c0 .806-1 1.462-2.243 1.462z");
}

.lgnwupbaj {
  fill: var(--svg-color--be202e, #be202e);
  d: path("M51.25 30.601c0 10.84-8.785 19.624-19.626 19.624S11.998 41.44 11.998 30.601s8.785-18.386 19.626-18.386S51.25 19.761 51.25 30.601");
}

.mrjy-p0fq {
  fill: var(--svg-color--25333a, #25333a);
}

.osb259-pf {
  fill: var(--svg-color--e7e6e6, #e7e6e6);
  d: path("M46.32 30.754c0 8.116-6.577 14.693-14.691 14.693S16.938 38.87 16.938 30.754c0-8.113 6.577-13.758 14.691-13.758S46.32 22.641 46.32 30.754");
}

</style>
