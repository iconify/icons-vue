<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG3z8vkejZ)" class="vipaeks7d"/><path fill="url(#SVGMTbKad4C)" class="lly3tsb6h"/><path fill="url(#SVGpwUwAO1U)" class="a-141rbsv"/><path fill="url(#SVGWBBqOc9T)" class="q5v9cudnr"/><path class="vrv5ydf4q"/><path class="zrtsbobez"/><defs><linearGradient id="SVG3z8vkejZ" x1="7.5" x2="17.456" y1="7.471" y2="20.528" gradientUnits="userSpaceOnUse"><stop class="vpfld-u2w"/><stop offset="1" class="lqi_cv96x"/></linearGradient><linearGradient id="SVGMTbKad4C" x1="3" x2="10.131" y1="5" y2="14.621" gradientUnits="userSpaceOnUse"><stop class="vpfld-u2w"/><stop offset="1" class="v-za7cc5j"/></linearGradient><linearGradient id="SVGpwUwAO1U" x1="12" x2="12" y1="5" y2="19" gradientUnits="userSpaceOnUse"><stop class="nk6lldb8c"/><stop offset="1" class="dae84s07o"/></linearGradient><linearGradient id="SVGWBBqOc9T" x1="7" x2="23.102" y1="10.727" y2="16.631" gradientUnits="userSpaceOnUse"><stop class="bq0y2srnj"/><stop offset="1" class="egrb4wlkv"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nsfw" /></template>
<style>
.a-141rbsv {
  d: path("M16.75 5L12 10.5h9z");
}

.bq0y2srnj {
  stop-color: var(--svg-color--4902cc, #4902cc);
}

.dae84s07o {
  stop-color: var(--svg-color--9300cb, #9300cb);
}

.egrb4wlkv {
  stop-color: var(--svg-color--8c04ee, #8c04ee);
}

.ft5dv1b6b {
  fill: none;
}

.lly3tsb6h {
  d: path("M12 19v-8.5h9z");
}

.lqi_cv96x {
  stop-color: var(--svg-color--a300d4, #a300d4);
}

.nk6lldb8c {
  stop-color: var(--svg-color--8605b8, #8605b8);
}

.q5v9cudnr {
  d: path("M7.25 5L12 10.5H3z");
}

.v-za7cc5j {
  stop-color: var(--svg-color--8c08a0, #8c08a0);
}

.vipaeks7d {
  d: path("M12 19v-8.5H3z");
}

.vpfld-u2w {
  stop-color: var(--svg-color--7a03b3, #7a03b3);
}

.vrv5ydf4q {
  fill: var(--svg-color--8e04e2, #8e04e2);
  d: path("M12 10.5V7.185L16.75 5z");
}

.zrtsbobez {
  fill: var(--svg-color--6801c2, #6801c2);
  d: path("M12 10.5V7.185L7.25 5z");
}

</style>
