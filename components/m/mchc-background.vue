<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGSvbEyccJ)" class="r4i437pya"/><path clip-rule="evenodd" class="urpw9ccch"/></g><defs><linearGradient id="SVGSvbEyccJ" x1="6.207" x2="17.586" y1="6.922" y2="17.576" gradientUnits="userSpaceOnUse"><stop class="bjqj0ue1i"/><stop offset="1" class="otg-tcc5v"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mchc-background" /></template>
<style>
.bjqj0ue1i {
  stop-color: var(--svg-color--e122fc, #e122fc);
}

.ft5dv1b6b {
  fill: none;
}

.otg-tcc5v {
  stop-color: var(--svg-color--26c5e2, #26c5e2);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.urpw9ccch {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M20 12a8 8 0 1 1-16 0a8 8 0 0 1 16 0M4.847 10.198l1.873.174c.014 1.11.259 3.327 1.115 3.341c.861.019 1.11-2.056 1.13-3.125h6.179c.018 1.069.268 3.144 1.129 3.125c.856-.014 1.101-2.23 1.115-3.341l1.873-.174c.442 1.826.127 3.425-.084 4c-2.128 2.07-4.405.884-5.318-.231c-.687-.847-1.459-1.073-1.803-1.082c-.352.01-1.12.235-1.811 1.082c-.909 1.12-3.186 2.301-5.313.23a7.6 7.6 0 0 1-.085-4m3.398-4.584A8 8 0 0 0 8.367 8.8c.052.179.254.518.645.428c.49-.108.414-.668.324-1.124c-.094-.457-.094-1.746 0-3.022c-.277.104-.88.358-1.091.532M15.718 8.8c.348-1.28.226-2.659.127-3.186c-.212-.174-.82-.423-1.092-.532c.09 1.276.09 2.565 0 3.022c-.094.456-.17 1.016.32 1.129c.39.085.593-.254.645-.433m-8.82-2.136c-.24.23-.776.79-.997 1.185c-.047.622 0 1.85.513 1.765c.645-.103.598-.63.438-1.412a9 9 0 0 1 .028-1.19c.01-.141.019-.26.019-.348m11.29 1.185c-.22-.395-.757-.955-.997-1.185c0 .089.004.202.018.348c.02.296.047.696.029 1.19c-.16.782-.212 1.309.437 1.412c.518.085.556-1.143.513-1.765m-7.153-3.223a9.5 9.5 0 0 1 1.977 0c.202 1.647.306 4.955-.908 5.002c-1.365.052-1.224-3.313-1.073-5.002z");
}

</style>
