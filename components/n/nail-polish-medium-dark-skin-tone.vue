<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="wo6vv39wk"/><path class="s079j_-3m"/><path class="fkzxvtbce"/><path class="dg9lnvbzf"/><path class="u5i9hzbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:nail-polish-medium-dark-skin-tone" /></template>
<style>
.dg9lnvbzf {
  fill: var(--svg-color--8899a6, #8899a6);
  d: path("m19 14l8-8l2 2l-8 8z");
}

.fkzxvtbce {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M13 16v4h2s2 0 6-4l-2-2s-2 2-6 2");
}

.s079j_-3m {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M16 24c0-1.657 0-8-3-8s-3 6.343-3 8a3 3 0 1 0 6 0m-9 3c0-1.657 0-8-3-8s-3 6.343-3 8a3 3 0 1 0 6 0m18 0c0-1.657 0-8-3-8s-3 6.343-3 8a3 3 0 0 0 6 0m9 5c0-1.657 0-8-3-8s-3 6.343-3 8a3 3 0 0 0 6 0");
}

.u5i9hzbsu {
  fill: var(--svg-color--8899a6, #8899a6);
  d: path("M27 6s-2-2 0-4l2-2h7v5l-3 3c-2 2-4 0-4 0z");
}

.wo6vv39wk {
  fill: var(--svg-color--af7e57, #af7e57);
  d: path("M27 36v-4s0-4 4-4s4 4 4 4v4zm-9 0v-9s0-4 4-4s4 4 4 4v9zm-9 0V24s0-4 4-4s4 4 4 4v12zm-9 0v-9s0-4 4-4s4 4 4 4v9z");
}

</style>
