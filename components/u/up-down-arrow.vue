<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="vvbxtxbac"/><g class="n1mjunbsu"><path class="iwqy4kbxy"/><path class="l80bfacuu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:up-down-arrow" /></template>
<style>
.iwqy4kbxy {
  d: path("m18.803 44.33l13.14 15.11l13.05-15.1c-.165-2.108-1.577-3.754-3.297-3.754h-2.915V26.894a4.174 4.174 0 0 0-4.174-4.173h-5.412a4.17 4.17 0 0 0-4.172 4.173v13.693h-2.917c-1.714 0-3.125 1.642-3.296 3.746");
}

.l80bfacuu {
  d: path("m18.803 19.464l13.14-15.11l13.04 15.1c-.165 2.108-1.577 3.754-3.297 3.754h-2.915v13.693a4.174 4.174 0 0 1-4.174 4.173h-5.412a4.17 4.17 0 0 1-4.172-4.173V23.208h-2.917c-1.714 0-3.125-1.642-3.296-3.746");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.vvbxtxbac {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M63.793 56.915a6.877 6.877 0 0 1-6.876 6.882H6.874A6.88 6.88 0 0 1 0 56.915V6.878A6.88 6.88 0 0 1 6.874 0h50.043c3.8 0 6.876 3.081 6.876 6.878z");
}

</style>
