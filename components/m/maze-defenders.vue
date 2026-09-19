<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a4-f2huvp"/><circle class="jwx-hyk9e"/><path class="tzclnbb6g"/><path class="riyit4a-a"/><path class="weji7vbsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:maze-defenders" /></template>
<style>
.a4-f2huvp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.638 14.456l.242-2.039");
}

.jwx-hyk9e {
  cx: 24px;
  cy: 5.638px;
  r: 2.139px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.riyit4a-a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.172 35.596v2.727L24 44.5l-6.172-6.177v-2.727m10.534-21.14l-.242-2.039m-4.12-.63l4.566.698a.302.302 0 0 0 .344-.346l-.297-1.877a.3.3 0 0 0-.258-.252L24 9.416l-4.355.594a.3.3 0 0 0-.258.252l-.297 1.877a.302.302 0 0 0 .344.346zm1.775-2.129V6.832");
}

.tzclnbb6g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.225 9.658V6.832m2.528 32.194l9.372-5.933a.96.96 0 0 0 .448-.814V16.327a1.05 1.05 0 0 0-.886-1.037L24 13.773l-9.687 1.517c-.51.08-.886.52-.886 1.037v15.952c0 .33.169.637.448.814l9.372 5.933c.46.291 1.046.291 1.506 0");
}

.weji7vbsq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.074 17.568v13.87l-8.07 5.11l-8.08-5.11v-13.87l5.16-.81l2.25 1.97c.38.33.95.33 1.33 0l2.25-1.97zM24 44.5v-5.255m0-27.458v1.986");
}

</style>
