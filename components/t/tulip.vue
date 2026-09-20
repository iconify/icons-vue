<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGIYX8adFc)" class="lfn56dbew"/><path fill="url(#SVGtemHWdyl)" class="x_6shujft"/><path fill="url(#SVGDiCtA3PV)" class="kskjyxbey"/><path fill="url(#SVGZtAusb4Z)" class="s6eruo7po"/><defs><linearGradient id="SVGIYX8adFc" x1="6.368" x2="17.719" y1="22.774" y2="22.456" gradientUnits="userSpaceOnUse"><stop class="wi7iq848b"/><stop offset="1" class="h2caqob_s"/></linearGradient><linearGradient id="SVGtemHWdyl" x1="12" x2="12" y1="2.479" y2="15.393" gradientUnits="userSpaceOnUse"><stop class="fcwq8gbdq"/><stop offset=".5" class="b9126b2qb"/><stop offset="1" class="h52_74aeo"/></linearGradient><linearGradient id="SVGDiCtA3PV" x1="6.538" x2="13.131" y1="4.011" y2="14.95" gradientUnits="userSpaceOnUse"><stop class="fcwq8gbdq"/><stop offset=".5" class="b9126b2qb"/><stop offset="1" class="h52_74aeo"/></linearGradient><linearGradient id="SVGZtAusb4Z" x1="17.477" x2="10.883" y1="4.027" y2="14.966" gradientUnits="userSpaceOnUse"><stop class="fcwq8gbdq"/><stop offset=".5" class="b9126b2qb"/><stop offset="1" class="h52_74aeo"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tulip" /></template>
<style>
.b9126b2qb {
  stop-color: var(--svg-color--5f7dc1, #5f7dc1);
}

.fcwq8gbdq {
  stop-color: var(--svg-color--d141e9, #d141e9);
}

.ft5dv1b6b {
  fill: none;
}

.h2caqob_s {
  stop-color: var(--svg-color--1be6b3, #1be6b3);
}

.h52_74aeo {
  stop-color: var(--svg-color--2bd9b9, #2bd9b9);
}

.kskjyxbey {
  d: path("M7.7 4.412c4.562 1.862 5.673 6.285 5.246 9.618a.977.977 0 0 1-1.378.76C8.6 13.542 5.427 10.528 6.296 5.179A1.014 1.014 0 0 1 7.7 4.407z");
  opacity: var(--svg-opacity--0-45, 0.45);
}

.lfn56dbew {
  d: path("M11.486 14.751v3.317c-1.199-2.129-3.858-3.029-5.658-3.029C5.828 19.442 9.495 21 12 21c2.51 0 6.172-1.558 6.172-5.961c-1.8 0-4.46.9-5.658 3.03V14.76c-.35.17-.689.155-1.028-.01");
  opacity: var(--svg-opacity--0-45, 0.45);
}

.s6eruo7po {
  d: path("M17.714 5.194c.771 5.056-2.304 8.291-5.272 9.598a.977.977 0 0 1-1.384-.751c-.468-3.297.407-7.705 5.257-9.623a1.013 1.013 0 0 1 1.399.771z");
  opacity: var(--svg-opacity--0-45, 0.45);
}

.wi7iq848b {
  stop-color: var(--svg-color--5784c2, #5784c2);
}

.x_6shujft {
  d: path("M12.787 3.394c3.076 3.991 1.94 8.4-.015 11.074a.952.952 0 0 1-1.559 0c-1.975-2.618-3.307-6.887-.01-11.074a.993.993 0 0 1 1.584 0");
  opacity: var(--svg-opacity--0-45, 0.45);
}

</style>
