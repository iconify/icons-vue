<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dgaydki2p"/><g class="y9tr6bcfx"><path class="fi-8e5b8q"/><rect class="hgh2xyb3u"/><circle class="jn8zzponk"/><path class="xzictkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pix-material-you" /></template>
<style>
.dgaydki2p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.286 12.197c.37 4.226 5.863 4.192 3.72 9.725c-1.793 3.844 2.981 6.561-1.642 10.28c-3.474 2.434-.698 7.174-6.561 8.084c-4.226.37-4.192 5.863-9.725 3.72c-3.844-1.793-6.561 2.981-10.28-1.642c-2.434-3.474-7.174-.698-8.084-6.561c-.37-4.226-5.863-4.192-3.72-9.724c1.793-3.845-2.981-6.562 1.642-10.281c3.474-2.434.698-7.174 6.562-8.084c4.225-.37 4.191-5.863 9.724-3.719c3.844 1.792 6.561-2.982 10.28 1.641c2.434 3.474 7.174.698 8.084 6.562Z");
}

.fi-8e5b8q {
  d: path("M13.5 13.5h8.75v8.75H13.5z");
}

.hgh2xyb3u {
  width: 8.75px;
  height: 8.75px;
  x: 25.75px;
  y: 25.75px;
  rx: 0.875px;
  ry: 0.875px;
}

.jn8zzponk {
  cx: 30.125px;
  cy: 17.875px;
  r: 4.375px;
}

.xzictkbiv {
  d: path("M22.25 30.125a4.375 4.375 0 1 0-4.375 4.375h4.375z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
