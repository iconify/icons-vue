<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hrk94sxea"/><path class="i8_keljbf"/><path class="a6ydb4bxt"/><path class="jk_-10-qd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tennis-racket-line-duotone" /></template>
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

.hrk94sxea {
  d: path("M18.8057 13.7481C15.919 16.6349 11.6641 17.0604 9.30218 14.6985C6.94028 12.3366 7.36578 8.08166 10.2526 5.19496C13.1393 2.30816 17.3942 1.88266 19.7561 4.24456C22.118 6.60646 21.6925 10.8614 18.8057 13.7481Z");
}

.i8_keljbf {
  d: path("M7.79285 10.3376L6.37235 16.2031L3.04605 19.5293C2.57095 20.0045 2.65015 20.5589 3.04605 20.9549C3.44205 21.3508 3.99645 21.43 4.47165 20.9549L7.79785 17.6286L13.6633 16.2081");
}

.jk_-10-qd {
  d: path("M18.0324 3.11621L8.17383 12.9748M20.884 5.96832L11.0254 15.8269M12.2383 3.69583L20.3045 11.762M8.75195 7.18112L16.8182 15.2473");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
