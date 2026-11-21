<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xmhp6hb5u"/><path class="f3-5il0pr"/><path class="mzsz8ybom"/><path class="ozukpcchl"/><path class="ya2rmdq5c"/><path class="ralo47bwr"/><path class="qe73yqbya"/><path class="y3h297b1b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:skiing-broken" /></template>
<style>
.f3-5il0pr {
  d: path("M15.1508 8.8429L10.5508 11.6429C9.45077 12.3429 9.65077 13.7429 10.8508 14.1429L12.9508 14.8429C13.8508 15.1429 14.1508 16.0429 13.6508 16.8429L12.5508 18.1762");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mzsz8ybom {
  d: path("M9.84921 13.0812L7.34961 15.8189");
}

.ozukpcchl {
  d: path("M15.1504 8.8429C16.1504 9.6429 17.1504 10.4429 18.3504 10.8429");
}

.qe73yqbya {
  d: path("M2.55078 13.6429L8.77568 16.4649");
}

.ralo47bwr {
  d: path("M12.75 8.78691L3.75 4.70691");
}

.xmhp6hb5u {
  d: path("M19.75 5.24292C19.75 6.34752 18.8546 7.24292 17.75 7.24292C16.6454 7.24292 15.75 6.34752 15.75 5.24292C15.75 4.13832 16.6454 3.24292 17.75 3.24292C18.8546 3.24292 19.75 4.13832 19.75 5.24292Z");
}

.y3h297b1b {
  d: path("M11.3242 17.6208L17.5491 20.4428C19.1491 21.1428 20.6491 20.6428 21.4491 19.2428");
}

.ya2rmdq5c {
  d: path("M15.1508 8.8429C14.0508 7.3429 12.9508 7.0429 11.5508 8.2429");
}

</style>
