<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="jdpw3kbnf"/><path class="krndxoigs"/><circle class="r-nlqvbfk"/><path class="kkcvlxypm"/><circle transform="rotate(-12.095 10.236 15.853)" class="igvmab_hp"/><path class="feb1n7r4p"/><path class="ivjgchuuo"/><path class="tyg8cd_pc"/><path class="jm_o-i1om"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:zany-face" /></template>
<style>
.feb1n7r4p {
  fill: var(--svg-color--65471b, #65471b);
  d: path("M18.625 20.937c-3.543.759-5.981.85-9.01.908c-.691.015-1.955.419-1.536 2.375c.838 3.911 6.379 7.837 12.642 6.495c6.262-1.342 9.708-7.194 8.87-11.105c-.419-1.956-1.739-1.808-2.375-1.536c-2.786 1.187-5.048 2.104-8.591 2.863");
}

.igvmab_hp {
  cx: 10.238px;
  cy: 15.857px;
  r: 1.942px;
  fill: var(--svg-color--292f33, #292f33);
}

.ivjgchuuo {
  fill: var(--svg-color--e8596e, #e8596e);
  d: path("M11 24.004v6c0 3 2 6 6 6s6-3 6-6v-6z");
}

.jdpw3kbnf {
  fill: var(--svg-color--ffcb4c, #ffcb4c);
  d: path("M35.597 14.232c2.083 9.72-4.108 19.289-13.828 21.372S2.48 31.496.397 21.776S4.506 2.487 14.225.404c9.72-2.084 19.289 4.108 21.372 13.828");
}

.jm_o-i1om {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.034 23.801s3.143.349 9.01-.908s8.591-2.864 8.591-2.864s-1.117 4.33-7.962 5.797s-9.639-2.025-9.639-2.025");
}

.kkcvlxypm {
  fill: var(--svg-color--f4f7f9, #f4f7f9);
  d: path("M14.088 14.282a3.938 3.938 0 1 1-7.7 1.65a3.938 3.938 0 0 1 7.7-1.65");
}

.krndxoigs {
  fill: var(--svg-color--f4f7f9, #f4f7f9);
  d: path("M29.284 9.012a6.734 6.734 0 1 1-13.169 2.821a6.734 6.734 0 0 1 13.169-2.821");
}

.r-nlqvbfk {
  cx: 22.306px;
  cy: 9.291px;
  r: 2.037px;
  fill: var(--svg-color--292f33, #292f33);
}

.tyg8cd_pc {
  fill: var(--svg-color--dd2f45, #dd2f45);
  d: path("M17 31.883a.545.545 0 0 0 .545-.545v-6.295h-1.091v6.295a.546.546 0 0 0 .546.545");
}

</style>
