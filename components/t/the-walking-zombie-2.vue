<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="a2_8khk-b"/><circle class="hxp-se7qa"/><path class="oag3m8y1m"/><circle class="bcnk8f9uo"/><path class="c37kfnbgi"/><path class="cnz84bbhh"/><path class="evovm3bcq"/><path class="pgj6eisgb"/><path class="v9bdavb7w"/><path class="x95fkm_io"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:the-walking-zombie-2" /></template>
<style>
.a2_8khk-b {
  cx: 16.931px;
  cy: 28.215px;
  r: 0.75px;
  fill: currentColor;
}

.bcnk8f9uo {
  cx: 38.914px;
  cy: 12.924px;
  r: 1.431px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.c37kfnbgi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.845 26.062l9.625-9.778M24.379 30.128l-8.166 2.58l-2.368-5.806s4.16-2.9 8.249-1.45");
}

.cnz84bbhh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.2 30.263s-1.456 2.483-1.8 2.674s-9.128 4.698-9.93 4.774s3.743-5.004 3.743-5.004");
}

.evovm3bcq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.314 37.663s-3.95-2.538-3.41-4.537s2.538-6.074 3.078-6.224s2.08 0 2.08 0");
}

.hxp-se7qa {
  cx: 19.655px;
  cy: 27.36px;
  r: 0.75px;
  fill: currentColor;
}

.oag3m8y1m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.056 25.375L37.018 8.792s2.863-.108 4.592 1.35c1.728 1.46 1.89 4.322 1.89 4.322L24.379 30.128z");
}

.pgj6eisgb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.66 23.862s-4.105 1.144-4.159 2.321s1.675 9.239 2.107 9.67s2.052 1.243 2.052 1.243l2.355-.406m-6.001-3.5l1.54-.496m-.981 2.429l1.54-.496");
}

.v9bdavb7w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.795 32.246c-.135-.197-3.87-2.752-3.866-2.928m5.879-1.748L9.242 22.3l.936-1.28l6.627-1.719l1.89.344l.974 1.89l.433 3.523");
}

.x95fkm_io {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.48 26.014l.083-3.16l-2.071-2.693m1.349 1.754l2.613-.246l.828 1.012v2.407m-3.578-3.352L8.66 23.863m2.187 7.775l2.482-1.413m-1.669 3.418l2.739-1.594m18.888 6.244l3.065.465m-1.517-10.681l3.065.464m-1.532-.232l-1.549 10.217m1.448.219l3.064.464m-1.516-10.68l3.065.464m-1.533-.232l-1.548 10.216");
}

</style>
