<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":274};
const content = `<path class="ivfw7bbfk"/><path class="dt7ct9j6e"/><path class="y77rdfs0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:tensorflow" /></template>
<style>
.dt7ct9j6e {
  fill: var(--svg-color--ed8e24, #ed8e24);
  d: path("M145.726 42.065L36.43 105.17v42.065l72.861-42.065v42.065l36.435-21.03zM255.022 63.1l-36.435 21.035v42.07l36.435-21.035zm-72.865 84.135l-36.43 21.035v42.07l36.43-21.036zm-36.43 63.104l-36.436-21.035v84.135l36.435-21.035z");
}

.ivfw7bbfk {
  fill: var(--svg-color--e55b2d, #e55b2d);
  d: path("M145.726 42.065v42.07l72.861 42.07v-42.07zM0 84.135v42.07l36.43 21.03V105.17zm109.291 21.035l-36.43 21.034v126.2l36.43 21.035v-84.135l36.435 21.035v-42.07l-36.435-21.034z");
}

.y77rdfs0t {
  fill: var(--svg-color--f8bf3c, #f8bf3c);
  d: path("M145.726 0L0 84.135l36.43 21.035l109.296-63.105l72.861 42.07L255.022 63.1zm0 126.204l-36.435 21.03l36.435 21.036l36.43-21.035z");
}

</style>
