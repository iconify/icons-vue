<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3b_n_bbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stockpot" /></template>
<style>
.n3b_n_bbn {
  fill: currentColor;
  d: path("M6.423 19q-1.01 0-1.716-.707T4 16.577V7.981h16v8.596q0 1.01-.707 1.716T17.577 19zM4 6.596v-1h5.5v-.769q0-.351.23-.59T10.317 4h3.366q.358 0 .587.238t.23.589v.77H20v1z");
}

</style>
