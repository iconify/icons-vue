<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrae4cb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:train" /></template>
<style>
.hrae4cb_h {
  fill: currentColor;
  d: path("M5 15.116V6q0-.979.563-1.574t1.524-.912T9.322 3.1T12 3q1.458 0 2.728.099t2.223.413t1.501.911T19 6v9.116q0 1.205-.84 2.045q-.839.839-2.044.839l1.5 1.5v.5h-.847l-2-2H9.231l-2 2h-.846v-.5l1.5-1.5q-1.206 0-2.045-.84Q5 16.322 5 15.116M6 11h5.5V6.539H6zm6.5 0H18V6.539h-5.5zm-3.204 4.3q.32-.314.32-.796q0-.481-.315-.8t-.796-.32t-.801.315t-.32.796t.315.801t.797.32t.8-.315m7 0q.32-.315.32-.796t-.315-.801t-.796-.32t-.801.315t-.32.796t.315.801t.796.32t.801-.315");
}

</style>
