<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="feq_dt35s"/><path class="x_jwp_bge"/><path class="a0gtrrbuj"/><path class="pw_kz6bsy"/><path class="p4-7k1g6n"/><path class="j8al4m6ce"/><path class="quhn2pcrw"/><path class="g8qpaoygp"/><path class="j9nl8b3qu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sun-2-broken" /></template>
<style>
.a0gtrrbuj {
  d: path("M12 20V22");
}

.feq_dt35s {
  d: path("M7.28451 10.3333C7.10026 10.8546 7 11.4156 7 12C7 14.7614 9.23858 17 12 17C14.7614 17 17 14.7614 17 12C17 9.23858 14.7614 7 12 7C11.4156 7 10.8546 7.10026 10.3333 7.28451");
}

.g8qpaoygp {
  d: path("M6.44531 17.5557L4.22309 19.7779");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j8al4m6ce {
  d: path("M19.7773 4.22217L17.5553 6.25375");
}

.j9nl8b3qu {
  d: path("M19.7773 19.7778L17.5553 17.5555");
}

.p4-7k1g6n {
  d: path("M22 12L20 12");
}

.pw_kz6bsy {
  d: path("M4 12L2 12");
}

.quhn2pcrw {
  d: path("M4.22266 4.22217L6.44467 6.25375");
}

.x_jwp_bge {
  d: path("M12 2V4");
}

</style>
