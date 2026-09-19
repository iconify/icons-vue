<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ra1-scbls"/><ellipse transform="rotate(-23.318 29.334 27.201)" class="jc295ub1f"/><ellipse transform="rotate(-61.669 19.765 28.053)" class="smas1pojk"/><path class="jylwq1mdg"/><path class="ntclzy0nt"/><circle class="xp3n4gbnf"/><circle class="gnev4fh0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:south-park-phone-destroyer-alt-2" /></template>
<style>
.gnev4fh0d {
  cx: 21.043px;
  cy: 27.961px;
  r: 0.75px;
  fill: currentColor;
}

.jc295ub1f {
  cx: 29.334px;
  cy: 27.201px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.197px;
  ry: 5.052px;
}

.jylwq1mdg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.826 20.027L34.82 11.83L8.87 15.016l1.006 8.197c.189 1.497.034 3.571-.538 5.784v0c-1.057 4.098-3.082 7.12-4.52 6.747c-1.44-.37-1.747-3.993-.69-8.092c.647-2.498 1.65-4.597 2.664-5.769l-1.103-8.976a3.49 3.49 0 0 1 3.035-3.888h.003L33.715 5.95a3.49 3.49 0 0 1 3.888 3.035v.003l1.154 9.388c1.213.938 2.595 2.654 3.755 4.79c2.018 3.72 2.594 7.31 1.29 8.017c-1.306.709-4-1.733-6.018-5.453c-1.144-2.109-1.821-4.179-1.958-5.703");
}

.ntclzy0nt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.902 23.446c8.423-2.619 17.034-3.712 25.95-3.169M7.958 32.767c1.432 3.05 3.783 5.507 6.895 7.11q4.94 2.547 10.906 2.144q6.068-.408 10.608-5.946c1.706-2.079 2.875-4.403 3.572-7.134");
}

.ra1-scbls {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.587 36.199l9.072-1.156a6.1 6.1 0 0 1-2.075 2.893q-.855.66-1.724 1.301q-1.305.285-4.45-2.135z");
}

.smas1pojk {
  cx: 19.765px;
  cy: 28.053px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.052px;
  ry: 4.197px;
}

.xp3n4gbnf {
  cx: 27.548px;
  cy: 27.353px;
  r: 0.75px;
  fill: currentColor;
}

</style>
