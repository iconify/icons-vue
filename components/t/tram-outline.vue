<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2kekxb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tram-outline" /></template>
<style>
.k2kekxb5g {
  fill: currentColor;
  d: path("M5 17.116V8q0-1.829 1.856-2.386T11.462 5l.75-1.5H7.077v-.885h9.846V3.5h-3.634l-.75 1.5q2.801.056 4.631.61Q19 6.167 19 8v9.116q0 1.205-.84 2.045q-.839.839-2.044.839l1.5 1.5v.5h-.847l-2-2H9.231l-2 2h-.846v-.5l1.5-1.5q-1.206 0-2.045-.84Q5 18.322 5 17.117M16.116 14H6h12zm-3.323 3.293q.323-.322.323-.793t-.323-.793q-.322-.323-.793-.323t-.793.323q-.323.322-.323.793t.323.793q.322.323.793.323t.793-.323M11.99 7.54h5.93H6.092zM6 13h12V8.539H6zm1.885 6h8.23q.785 0 1.335-.55t.55-1.335V14H6v3.116q0 .784.55 1.334t1.335.55m4.104-13q-3.1 0-4.377.401t-1.52 1.138H17.92q-.242-.754-1.53-1.147T11.989 6");
}

</style>
