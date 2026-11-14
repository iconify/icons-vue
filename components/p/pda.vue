<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cci8dpbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pda" /></template>
<style>
.cci8dpbku {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.625 1.75h-3.75q-2.123 0-3.624 1.501T1.75 6.875v10.25q0 2.123 1.501 3.624t3.624 1.501h3.75q2.123 0 3.624-1.501t1.501-3.624V6.875q0-2.123-1.501-3.624T10.625 1.75m11.114 1.88l-3 17q-.013.073-.04.142t-.067.131q-.039.062-.09.116q-.051.053-.112.095q-.06.043-.128.073t-.14.045t-.146.018t-.146-.011q-.073-.013-.142-.04t-.131-.067q-.062-.039-.116-.09q-.053-.051-.095-.112q-.043-.06-.073-.128t-.045-.14t-.018-.146t.011-.146l3-17q.026-.147.107-.273q.08-.126.202-.211q.122-.086.268-.118q.145-.033.292-.007q.073.013.142.04t.131.067t.116.09t.095.112q.043.06.073.128t.045.14t.018.146t-.011.146M10.25 4.75q1.036 0 1.768.732t.732 1.768v3q0 1.036-.732 1.768t-1.768.732h-3q-1.036 0-1.768-.732T4.75 10.25v-3q0-2.5 2.5-2.5zM6.5 16.5q0-2.25 2.25-2.25T11 16.5t-2.25 2.25T6.5 16.5");
}

</style>
