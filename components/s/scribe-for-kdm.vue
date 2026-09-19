<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sxe6np5ne"/><path class="i5_nfnb1r"/><path class="f9ud5mvub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:scribe-for-kdm" /></template>
<style>
.f9ud5mvub {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.304 19.112s-.72 4.214-.88 5.387c.933.623 2.783.846 3.96.378c.052-1.157.156-5.44.156-5.44l.395-.111l-1.42-1.038s.006-.312.01-.412c.005-.124-.075-.134-.228-.143c-.373-.019-.002-.01-.376-.02c-.167-.004-.232-.008-.245.143c-.017.205-.024.39-.024.39l-1.837.683zm17.392 0s.72 4.214.88 5.387c-.933.623-2.783.846-3.96.378c-.051-1.157-.156-5.44-.156-5.44l-.395-.111l1.42-1.038s-.006-.312-.01-.412c-.005-.124.075-.134.228-.143c.373-.019.003-.01.376-.02c.167-.004.232-.008.245.143c.017.205.024.39.024.39l1.837.683zM24 27.786v-4.413m0-3.743v-.162m0-2.252v.76m0 3.146v.759");
}

.i5_nfnb1r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.278 30.98s.39-.614.68-.861c.196-.166.613-.407 1.042-.407s.846.24 1.042.407c.29.247.68.862.68.862m-2.65-15.183s-2.788-1.233-5.133-.513s-4.533.448-5.89-.64c-.264.856-3.732 12.106-4.468 14.432c8.523-2.082 10.216-1.677 14.581-.25m2.774-13.007s2.78-1.255 5.126-.535s4.532.448 5.889-.64c.264.856 3.733 12.106 4.469 14.432c-8.524-2.082-10.217-1.677-14.582-.25");
}

.sxe6np5ne {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.355 16.898s-1.052-.274-2.443.28c-.305 1.02-4.412 15.04-4.412 15.04s13.586-.045 16.64-.049c.61 0 1.475.354 1.825.746c.362.406.814.44 1.035.44s.674-.034 1.035-.44c.35-.392 1.214-.746 1.825-.746c3.055.004 16.64.049 16.64.049s-4.107-14.02-4.412-15.04c-1.391-.554-2.442-.28-2.442-.28");
}

</style>
