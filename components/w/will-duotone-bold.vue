<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t4wfbu4kp"/><path class="izqo6krhl"/><path class="i1q4_4p7l"/><path class="ky4omnbla"/><path class="zwh7a2bjz"/><path class="l9gunc5ss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:will-duotone-bold" /></template>
<style>
.i1q4_4p7l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 15 3 -3 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.izqo6krhl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 9h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ky4omnbla {
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
}

.l9gunc5ss {
  d: path("m8 15 3 -3 2 2 3 -3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t4wfbu4kp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zwh7a2bjz {
  d: path("M6 9h9");
}

</style>
