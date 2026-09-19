<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="j_dgrcvfo"/><path class="db17tzq7n"/><circle class="vo23qzbdz"/><path class="xbll6nbbd"/><circle class="kguly92mf"/><path class="qzoxviblg"/><circle class="nddl6jb7u"/><circle class="atebzpbqo"/><circle class="nn3l02jii"/><circle class="wqvfjibgs"/><path class="aw4nwjgft"/><circle class="yjii5n59a"/><circle class="klb0vlb2n"/><circle class="fug0qob4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:trussme" /></template>
<style>
.atebzpbqo {
  cx: 8.81px;
  cy: 8.8px;
  r: 0.75px;
  fill: currentColor;
}

.aw4nwjgft {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 13.8v-10m28.7 38.7h10");
}

.db17tzq7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.82 5.5a3.3 3.3 0 1 1 0 6.6H5.5V5.5zM35.9 39.19a3.3 3.3 0 1 1 6.6 0v3.32h-6.6z");
}

.fug0qob4u {
  cx: 35.9px;
  cy: 44.129px;
  r: 1.629px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j_dgrcvfo {
  cx: 39.2px;
  cy: 8.8px;
  r: 3.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kguly92mf {
  cx: 24px;
  cy: 24px;
  r: 7.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.klb0vlb2n {
  cx: 42.5px;
  cy: 44.129px;
  r: 1.629px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nddl6jb7u {
  cx: 39.2px;
  cy: 8.8px;
  r: 0.75px;
  fill: currentColor;
}

.nn3l02jii {
  cx: 39.2px;
  cy: 39.2px;
  r: 0.75px;
  fill: currentColor;
}

.qzoxviblg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.867 11.133l-7.575 7.575M11.154 36.867L18.72 29.3m-9.9-17.2v23.8");
}

.vo23qzbdz {
  cx: 8.82px;
  cy: 39.2px;
  r: 3.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wqvfjibgs {
  cx: 8.81px;
  cy: 39.2px;
  r: 0.75px;
  fill: currentColor;
}

.xbll6nbbd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.12 39.2H35.9m3.3-3.31V12.1m-3.3-3.3H12.12");
}

.yjii5n59a {
  cx: 39.2px;
  cy: 44.129px;
  r: 1.629px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
