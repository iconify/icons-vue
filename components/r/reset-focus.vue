<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvhcmcccv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:reset-focus" /></template>
<style>
.hvhcmcccv {
  fill: currentColor;
  d: path("M12 16v-2.5q0-.625.438-1.062T13.5 12H16v1.5h-2.5V16zm1.5 6q-.625 0-1.062-.437T12 20.5V18h1.5v2.5H16V22zm7-6v-2.5H18V12h2.5q.625 0 1.063.438T22 13.5V16zM18 22v-1.5h2.5V18H22v2.5q0 .625-.437 1.063T20.5 22zm2.775-12H18.7q-.65-2.2-2.475-3.6T12 5Q9.075 5 7.037 7.038T5 12q0 1.8.813 3.3T8 17.75V15h2v6H4v-2h2.35Q4.8 17.75 3.9 15.938T3 12q0-1.875.713-3.512t1.924-2.85t2.85-1.925T12 3q3.225 0 5.663 1.988T20.775 10");
}

</style>
