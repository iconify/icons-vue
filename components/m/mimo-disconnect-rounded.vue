<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuiok3igl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mimo-disconnect-rounded" /></template>
<style>
.iuiok3igl {
  fill: currentColor;
  d: path("M3.175 3.175v2.8L1.4 4.2q-.275-.275-.275-.7t.275-.7t.7-.275t.7.275l18.4 18.4q.275.275.275.7t-.275.7t-.7.275t-.7-.275L15.2 18H17l.7.7q.15.15.225.338t.075.387V20q0 .425-.288.712T17 21H7q-.425 0-.712-.288T6 20v-.575q0-.2.075-.387T6.3 18.7L7 18H4q-.825 0-1.412-.587T2 16V5q0-.925.588-1.375zM20 3q.825 0 1.413.588T22 5v11.725q0 .675-.612.938T20.3 17.45L7.55 4.7q-.475-.475-.212-1.088T8.275 3z");
}

</style>
