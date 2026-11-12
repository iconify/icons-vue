<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="x_jwp_bge"/><path class="a0gtrrbuj"/><path class="mhrx-fb4o"/><path class="hk3yrq41f"/><path class="wruedxb7y"/><path class="fw0v9lbrp"/><path class="tiz_macsu"/><path class="vwck1pjsf"/><path class="dvs6ehbur"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-shine-broken" /></template>
<style>
.a0gtrrbuj {
  d: path("M12 20V22");
}

.dvs6ehbur {
  d: path("M15.2653 14.6272C15.3921 15.9353 15.4554 16.5894 15.0724 16.8801C14.6894 17.1709 14.1137 16.9058 12.9622 16.3756L12.6643 16.2384L12.6643 16.2384C12.337 16.0878 12.1734 16.0124 12 16.0124C11.8266 16.0124 11.663 16.0878 11.3357 16.2384L11.0378 16.3756L11.0378 16.3756C9.88634 16.9058 9.31059 17.1709 8.92757 16.8801C8.54456 16.5894 8.60794 15.9353 8.7347 14.6272L8.76749 14.2888C8.80351 13.9171 8.82152 13.7312 8.76793 13.5589C8.71434 13.3865 8.59521 13.2472 8.35696 12.9686L8.14005 12.715C7.30162 11.7345 6.88241 11.2443 7.02871 10.7739C7.13469 10.4331 7.4866 10.2661 8.14005 10.0942M10.5766 8.70419C11.2099 7.56806 11.5266 7 12 7C12.4734 7 12.7901 7.56806 13.4234 8.70419L13.5873 8.99812L13.5873 8.99813C13.7672 9.32097 13.8572 9.48239 13.9975 9.5889C14.1378 9.69541 14.3126 9.73495 14.6621 9.81402L14.9802 9.88601C16.2101 10.1643 16.825 10.3034 16.9713 10.7739C17.0769 11.1134 16.8879 11.4631 16.4595 12");
}

.fw0v9lbrp {
  d: path("M17.6572 6.34314L18.0005 5.99988");
}

.hk3yrq41f {
  d: path("M20 12L22 12");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mhrx-fb4o {
  d: path("M2 12L4 12");
}

.tiz_macsu {
  d: path("M18 18.0001L17.657 17.6571");
}

.vwck1pjsf {
  d: path("M6.34375 6.34326L6.00049 6");
}

.wruedxb7y {
  d: path("M6 17.9999L6.34305 17.6568");
}

.x_jwp_bge {
  d: path("M12 2V4");
}

</style>
