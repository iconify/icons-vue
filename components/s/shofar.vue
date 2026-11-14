<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv290chln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:shofar" /></template>
<style>
.nv290chln {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.75 5q0-2.5 5.25-2.5q2.005 0 3.454.564Q21.25 3.762 21.25 5q0 6.331-4.66 10.94q-4.638 4.586-11.992 5.554q-.069.009-.139.005q-.069-.004-.137-.02q-.068-.017-.131-.046q-.064-.029-.121-.069t-.106-.089t-.087-.108q-.039-.058-.067-.122q-.027-.064-.042-.132l-.5-2.25q-.014-.064-.017-.13q-.003-.065.005-.13t.028-.128t.05-.12q.03-.059.07-.111t.088-.096t.104-.08t.116-.06Q10.75 14.875 10.75 5m4.785 9.873q3.511-3.472 4.097-8.009q-.087.037-.178.072Q18.005 7.5 16 7.5q-2.507 0-3.817-.57q-.636 8.873-7.318 12.007l.216.971q6.389-1.015 10.454-5.035");
}

</style>
