<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fu3f8gbea"/><path class="k6vs9e71h"/><path class="tdo8owfww"/><path class="fw42j47bm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stats-royale" /></template>
<style>
.fu3f8gbea {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.673 14.448H20.3c1.01 0 1.822.813 1.822 1.822v2.69c0 1.01-.813 1.823-1.822 1.823H8.673A1.82 1.82 0 0 1 6.85 18.96v-2.69c0-1.01.812-1.823 1.822-1.823m19.028.001h11.627c1.01 0 1.822.813 1.822 1.822v2.69c0 1.01-.812 1.823-1.822 1.823H27.7a1.82 1.82 0 0 1-1.822-1.822v-2.69c0-1.01.813-1.823 1.822-1.823m-21.752 0h36.104m-5.441-2.386l-1.108-7.514H30.02l.389 2.645h-3.032l-.56-2.647h-6.188l-.56 2.647h-3.032l.39-2.645H11.94l-1.108 7.514Z");
}

.fw42j47bm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.962 27.715v-4.906h3.662v1.571h3.59c1.463.912 2.824 1.889 4.613 1.889s3.15-.977 4.614-1.889h3.59v-1.57h3.661v4.905zm3.909.205c.94 2.46 4.734 2.514 8.129 2.514s7.188-.054 8.129-2.514");
}

.k6vs9e71h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.777 17.856l1.027-.547h3.234l.938.357m17.247.19l-1.027-.547h-3.234l-.938.357m-22.026 3.55L5.5 27.968l1.844 1.63l-.854 6.242L24 43.454l17.51-7.614l-.854-6.242l1.844-1.63l-2.498-6.752");
}

.tdo8owfww {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.319 21.146l-.943 6.046l10.815 7.749L24 33.726l3.81 1.215l10.814-7.75l-.943-6.045");
}

</style>
