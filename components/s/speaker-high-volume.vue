<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="vydax7v4x"/><path class="xkyc71v3c"/><path class="f51lt6y1i"/><path class="fymgdbrdm"/><path class="qodusnydq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:speaker-high-volume" /></template>
<style>
.f51lt6y1i {
  fill: var(--svg-color--8899a6, #8899a6);
  d: path("M29 32.019a.945.945 0 0 1-.615-1.666c3.603-3.071 5.668-7.551 5.668-12.29s-2.066-9.219-5.669-12.29a.947.947 0 0 1 1.229-1.44a18.02 18.02 0 0 1 6.333 13.73a18.02 18.02 0 0 1-6.332 13.729a.94.94 0 0 1-.614.227");
}

.fymgdbrdm {
  fill: var(--svg-color--8899a6, #8899a6);
  d: path("M26.27 28.959a.927.927 0 0 1-.592-1.645a12.04 12.04 0 0 0 4.394-9.315a12.05 12.05 0 0 0-4.311-9.245a.929.929 0 0 1 1.196-1.422a13.9 13.9 0 0 1 4.973 10.667c0 4.172-1.848 8.089-5.069 10.746a.92.92 0 0 1-.591.214");
}

.qodusnydq {
  fill: var(--svg-color--8899a6, #8899a6);
  d: path("M23.709 25.959a.998.998 0 0 1-.636-1.772A7.98 7.98 0 0 0 26 18a7.97 7.97 0 0 0-2.988-6.236a1 1 0 1 1 1.254-1.558A9.96 9.96 0 0 1 28 18a9.97 9.97 0 0 1-3.657 7.731a1 1 0 0 1-.634.228");
}

.vydax7v4x {
  fill: var(--svg-color--8899a6, #8899a6);
  d: path("M2 10s-2 0-2 2v12c0 2 2 2 2 2h6l8 8s1 1 2 1h1s1 0 1-1V2s0-1-1-1h-1c-1 0-2 1-2 1l-8 8z");
}

.xkyc71v3c {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("m8 26l8 8s1 1 2 1h1s1 0 1-1V2s0-1-1-1h-1c-1 0-2 1-2 1l-8 8z");
}

</style>
