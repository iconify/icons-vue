<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="mc-vbtb-v"><path class="a967xdbld"/><path class="ln44-3bvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:registered" /></template>
<style>
.a967xdbld {
  d: path("M32 2C18.2 2 7 13.2 7 27s11.2 25 25 25s25-11.2 25-25S45.8 2 32 2m0 45c-11 0-20-9-20-20S21 7 32 7s20 9 20 20s-9 20-20 20");
}

.ln44-3bvc {
  d: path("M32.3 14H23v26h4.2v-7.7h7l4.4 7.7H43l-5-9c7.7-3.4 7.7-17-5.7-17m.5 15h-5.6V17.3h5.6c8.8 0 8.8 11.7 0 11.7");
}

.mc-vbtb-v {
  fill: var(--svg-color--4d5357, #4d5357);
}

</style>
