<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="zdrma3cri"/><path class="oy6isrkvx"/><path class="rj3l5ub_o"/><path class="qt14o67pf"/><path class="mg5hj5h_e"/><path class="u-v1_zxca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:rainbow" /></template>
<style>
.mg5hj5h_e {
  fill: var(--svg-color--5c903f, #5c903f);
  d: path("M9.083 36h3c0-13.217 10.705-23.935 23.917-23.957v-3C21.13 9.065 9.083 21.125 9.083 36");
}

.oy6isrkvx {
  fill: var(--svg-color--eb2027, #eb2027);
  d: path("M0 35.999h3.042c0-18.189 14.734-32.935 32.917-32.957V0C16.095.023 0 16.131 0 35.999");
}

.qt14o67pf {
  fill: var(--svg-color--ffcb4c, #ffcb4c);
  d: path("M6.083 36h3C9.083 21.125 21.13 9.065 36 9.043v-3C19.473 6.065 6.083 19.468 6.083 36");
}

.rj3l5ub_o {
  fill: var(--svg-color--f19020, #f19020);
  d: path("M3.083 36h3C6.083 19.468 19.473 6.065 36 6.043v-3C17.817 3.065 3.083 17.811 3.083 36");
}

.u-v1_zxca {
  fill: var(--svg-color--226798, #226798);
  d: path("M12.083 36h3c0-11.56 9.362-20.934 20.917-20.956v-3.001C22.788 12.065 12.083 22.783 12.083 36");
}

.zdrma3cri {
  fill: var(--svg-color--8767ac, #8767ac);
  d: path("M36 1C16.118 1 1 16.118 1 36h17.042c0-9.917 8.042-17.958 17.958-17.958z");
}

</style>
