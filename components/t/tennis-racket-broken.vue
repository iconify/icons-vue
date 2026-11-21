<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u3yzzob8j"/><path class="i8_keljbf"/><path class="a6ydb4bxt"/><path class="x5z_igxjl"/><path class="moll-mbii"/><path class="t-ll26bdz"/><path class="ybq-sz3rh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tennis-racket-broken" /></template>
<style>
.a6ydb4bxt {
  d: path("M6.37109 16.2031L7.79659 17.6286");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i8_keljbf {
  d: path("M7.79285 10.3376L6.37235 16.2031L3.04605 19.5293C2.57095 20.0045 2.65015 20.5589 3.04605 20.9549C3.44205 21.3508 3.99645 21.43 4.47165 20.9549L7.79785 17.6286L13.6633 16.2081");
}

.moll-mbii {
  d: path("M20.884 5.96826L11.0254 15.8269");
}

.t-ll26bdz {
  d: path("M12.2383 3.6958L20.3045 11.762");
}

.u3yzzob8j {
  d: path("M10.811 4.68097C13.6655 2.26577 17.5423 2.03077 19.7561 4.24457C22.118 6.60647 21.6925 10.8614 18.8057 13.7481C15.919 16.6349 11.6641 17.0604 9.30219 14.6985C7.38739 12.7837 7.30459 9.62477 8.87989 6.95937");
}

.x5z_igxjl {
  d: path("M18.0324 3.11621L8.17383 12.9748");
}

.ybq-sz3rh {
  d: path("M8.75195 7.18091L16.8182 15.2471");
}

</style>
