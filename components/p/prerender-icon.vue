<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":192};
const content = `<path class="epwejjbrp"/><path class="jga08ib1n"/><path class="b4q_rrw0w"/><path class="o-dux6biz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:prerender-icon" /></template>
<style>
.b4q_rrw0w {
  fill: var(--svg-color--f0da50, #f0da50);
  d: path("M160 128c-17.673 0-32 14.327-32 32v32h64v-64z");
}

.epwejjbrp {
  fill: var(--svg-color--f0da50, #f0da50);
  d: path("M64 0v64h32c17.673 0 32-14.327 32-32V0z");
}

.jga08ib1n {
  fill: var(--svg-color--4bc69a, #4bc69a);
  d: path("M32 0C14.327 0 0 14.327 0 32v128c0 17.673 14.327 32 32 32h32V0z");
}

.o-dux6biz {
  fill: var(--svg-color--5d7b8c, #5d7b8c);
  d: path("M224 0h-32v192h32c17.673 0 32-14.327 32-32V32c0-17.673-14.327-32-32-32");
}

</style>
