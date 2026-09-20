<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="vymhtugro"/><path class="n0_hsac9j"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xpx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.n0_hsac9j {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.188 4.195c-2.046.422-4.132 1.29-4.92 1.67c-.197 2.861.77 5.635 1.28 6.664c1.598-2.009 4.529-4.218 5.277-4.73c.509-.348.321-.815.185-1.065c-.507-.926-1.425-2.078-1.822-2.539M19.27 5.633c-3.248-1.558-6.958-1.718-8.407-1.604c1.299.76 2.05 1.752 2.402 2.006c.282.204.674.145.834.09c1.72-.72 4.165-.628 5.171-.492m.482.794c.119 3.572-1.623 7.175-2.51 8.531c0-.25-1.403-4.581-1.865-5.544c-.37-.77-.236-1.18 0-1.344c1.876-1.315 3.698-1.643 4.375-1.643m-7.831 3.352c-2.288.9-4.985 2.823-6.047 3.673c1.554 3.375 4.762 5.772 6.172 6.548c2.139-1.35 3.855-3.23 4.445-4.001c-.9-2.36-3.015-5.548-3.45-6.064c-.349-.413-.849-.263-1.12-.156");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vymhtugro {
  fill: var(--svg-color--f3a91d, #f3a91d);
  d: path("M24 0H0v24h24z");
}

</style>
