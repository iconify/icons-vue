<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f02vt5b-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sprint-sharp" /></template>
<style>
.f02vt5b-e {
  fill: currentColor;
  d: path("M5.4 20L4 18.6L13.6 9H11v2H9V7h5.825q.4 0 .775.15t.65.425l3 2.975q.675.675 1.65 1.05t2.1.4v2q-1.55 0-2.812-.475T17.95 12.1l-1-1.05l-2.2 2.2L17 15.5l-6.55 3.775l-1-1.725l4.3-2.475l-1.7-1.7zM3 13v-2h5v2zm-2-3V8h5v2zm18.475-2q-.825 0-1.425-.587T17.45 6t.6-1.412T19.475 4t1.425.588T21.5 6t-.6 1.413T19.475 8M3 7V5h5v2z");
}

</style>
