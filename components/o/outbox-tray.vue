<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="nxvp979uw"/><path class="nt31-o_uh"/><path class="khpjc8-nz"/><path class="bxo09ebpl"/><path class="yvme9ebwu"/><path class="bvo6f9bjh"/><path class="pfoar6znl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:outbox-tray" /></template>
<style>
.bvo6f9bjh {
  fill: var(--svg-color--881a0e, #881a0e);
  d: path("m37.9 0l2.4 5.5s-9.1 5.3-11 17.5c-1.7 11.3 2.5 19 2.5 19l1.2.8s-1.4-8.9 3.5-16.8c3-4.8 7.1-7.9 8.5-8.8l2 4.7l1.5 1.5L60 4l-1.5-1.5z");
}

.bxo09ebpl {
  fill: var(--svg-color--d3976e, #d3976e);
  d: path("M35.4 47.5s-.3 7-1.7 8.3c-2.7 2.6-11.1 2.6-13.9 0c-1.4-1.3-1.7-8.3-1.7-8.3H0V64h53.5V47.5z");
}

.khpjc8-nz {
  fill: var(--svg-color--f2bc97, #f2bc97);
  d: path("M24.9 51.4L0 64h53.5L64 51.4z");
}

.nt31-o_uh {
  fill: var(--svg-color--b77e58, #b77e58);
  d: path("M24.9 39H64v12.3H24.9z");
}

.nxvp979uw {
  fill: var(--svg-color--89664c, #89664c);
  d: path("M24.9 39v12.4L0 64V47.5z");
}

.pfoar6znl {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M33.2 42.9s-.1-7 4-15.4c3.4-6.9 9.1-9.7 9.1-9.7l2.5 5.7L60 4L39.4 1.5L41.8 7s-9.1 5.3-11 17.5c-1.6 11.3 2.4 18.4 2.4 18.4");
}

.yvme9ebwu {
  fill: var(--svg-color--89664c, #89664c);
  d: path("M64 51.4L53.5 64V47.5L64 39z");
}

</style>
