<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hh-17ybak"/><path class="dmgzojbvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pill-broken" /></template>
<style>
.dmgzojbvz {
  d: path("M16.8057 7.19434C16.8057 7.19434 16.2649 9.99999 13.1322 13.1327C9.99952 16.2653 7.19434 16.8057 7.19434 16.8057");
}

.hh-17ybak {
  d: path("M2.60045 6C2.92903 5.27154 3.39259 4.58912 3.99114 3.99057C6.64524 1.33648 10.9484 1.33648 13.6025 3.99057L20.01 10.3981C21.0296 11.4177 21.6575 12.6807 21.8937 14M2.10742 10C2.34364 11.3193 2.97155 12.5823 3.99114 13.6019L10.3987 20.0094C13.0528 22.6635 17.3559 22.6635 20.01 20.0094C20.6086 19.4109 21.0721 18.7285 21.4007 18");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
