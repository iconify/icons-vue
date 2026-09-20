<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="y1ctrtb9i"/><path class="pynnv_sfv"/><path class="pegpy-6br"/><path class="o0knz9bor"/><path class="b76lxvbxi"/><path class="eianevb9g"/><path class="i37u1lbql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wbeth" /></template>
<style>
.b76lxvbxi {
  fill: var(--svg-color--130f03, #130f03);
  d: path("M12 14.117L15.706 12L12 10.411z");
}

.eianevb9g {
  fill: var(--svg-color--868686, #868686);
  d: path("m12.001 14.884l-3.706-2.091l3.706 5.03z");
}

.ft5dv1b6b {
  fill: none;
}

.i37u1lbql {
  fill: var(--svg-color--312807, #312807);
  d: path("m12 14.884l3.706-2.091L12 17.823z");
}

.o0knz9bor {
  fill: var(--svg-color--363636, #363636);
  d: path("M12.001 14.117L8.295 12l3.706-1.588z");
}

.pegpy-6br {
  fill: var(--svg-color--312706, #312706);
  d: path("m12 10.422l3.706 1.577C14.467 10.093 12 6.271 12 6.176z");
}

.pynnv_sfv {
  fill: var(--svg-color--868686, #868686);
  d: path("m12.001 10.422l-3.706 1.577c1.234-1.906 3.706-5.728 3.706-5.823z");
}

.y1ctrtb9i {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.184 18.543A8.97 8.97 0 0 1 12 21c-2.356 0-4.5-.9-6.099-2.382l.747-.752A7.9 7.9 0 0 0 12 19.94a7.9 7.9 0 0 0 5.432-2.15zm.65-.688A8.96 8.96 0 0 0 21 12c0-2.35-.9-4.495-2.382-6.099l-.742.752A7.92 7.92 0 0 1 19.941 12a7.9 7.9 0 0 1-1.858 5.104zM6.897 5.917A7.9 7.9 0 0 1 12 4.059a7.9 7.9 0 0 1 5.188 1.932l.757-.752A9 9 0 0 0 12 3a8.94 8.94 0 0 0-5.855 2.17zm-.688.651l-.752-.752A8.97 8.97 0 0 0 3 12c0 2.276.847 4.357 2.24 5.94l.751-.752A7.9 7.9 0 0 1 4.06 12c0-2.102.815-4.013 2.15-5.432");
}

</style>
