<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="taiundbtb"/><path class="xfcsm6b8b"/><path class="bbj_fcggl"/><path class="d8xq11pqp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paper-bin-linear" /></template>
<style>
.bbj_fcggl {
  d: path("M19 19H5");
}

.d8xq11pqp {
  stroke-linejoin: round;
  d: path("M14 6L12 8M12 8L9 11M12 8L10 6M12 8L15 11M9 11L6.16129 13.8387M9 11L6.10526 8.10526M9 11L12 14M6.16129 13.8387L4.08687 15.9131M6.16129 13.8387L3.5 11L6.10526 8.10526M6.16129 13.8387L9.06452 16.9355M20 6L15 11M15 11L12 14M15 11L19.913 15.913M12 14L9.06452 16.9355M12 14L17 19M9.06452 16.9355L7 19M9.06452 16.9355L11 19M4 6L6.10526 8.10526M6.10526 8.10526L8 6M13 19L20.5 11L16 6");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.taiundbtb {
  d: path("M10.1673 22H13.833C16.2979 22 17.5303 22 18.3743 21.2732C19.2182 20.5464 19.401 19.3276 19.7666 16.89L20.9666 8.89004C21.4472 5.68646 21.6874 4.08466 20.7898 3.04233C19.8922 2 18.2724 2 15.033 2H8.96727C5.72784 2 4.10813 2 3.21049 3.04233C2.31285 4.08466 2.55311 5.68645 3.03365 8.89004L4.23365 16.89C4.59929 19.3276 4.78211 20.5464 5.62604 21.2732C6.46997 22 7.7024 22 10.1673 22Z");
}

.xfcsm6b8b {
  d: path("M21 6H3");
}

</style>
