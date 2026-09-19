<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><g class="nv_n5pb_p"><ellipse transform="rotate(-65.001 52.5 31.313)" class="enluamb7l"/><ellipse transform="rotate(-25.001 11.5 31.311)" class="h1j_y6bll"/></g><path class="sk-9nisvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:persevering-face" /></template>
<style>
.enluamb7l {
  cx: 52.5px;
  cy: 31.3px;
  opacity: var(--svg-opacity--0-8, 0.8);
  rx: 6.5px;
  ry: 9px;
}

.h1j_y6bll {
  cx: 11.5px;
  cy: 31.3px;
  opacity: var(--svg-opacity--0-8, 0.8);
  rx: 9px;
  ry: 6.5px;
}

.nv_n5pb_p {
  fill: var(--svg-color--ff717f, #ff717f);
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.sk-9nisvc {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M19.4 42.2c8.1-5.7 17.1-5.6 25.2 0c1 .7 1.8-.5 1.2-1.6c-2.5-4-7.4-7.7-13.8-7.7s-11.3 3.6-13.8 7.7c-.6 1.1.2 2.3 1.2 1.6m32.3-27.1c.6.3.3 1-.2 1.1c-2.7.4-5.5.9-8.3 2.4c4 .7 7.2 2.7 9 4.8c.4.5-.1 1.1-.5 1c-4.8-1.7-9.7-2.7-15.8-2c-.5 0-.9-.2-.8-.7c1.6-7.3 10.9-10 16.6-6.6m-39.4 0c-.6.3-.3 1 .2 1.1c2.7.4 5.5.9 8.3 2.4c-4 .7-7.2 2.7-9 4.8c-.4.5.1 1.1.5 1c4.8-1.7 9.7-2.7 15.8-2c.5 0 .9-.2.8-.7c-1.6-7.3-10.9-10-16.6-6.6");
}

</style>
