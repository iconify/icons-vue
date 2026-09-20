<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="kdba2ab1g"/><path class="w3r8b8nla"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rvc-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kdba2ab1g {
  fill: var(--svg-color--27a986, #27a986);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.w3r8b8nla {
  fill: var(--svg-color--fff, #fff);
  d: path("m14.808 6.093l-4.752 1.526l5.275.698zM9.97 7.49l.609-1.134l2.616-1.046zm.609-1.221l.305-.872l2.137-.087zm3.531-.656l.306-.829l.349 1.134zm-.043 0l.305-.829l-1.526-.653zm-1.439-1.569l-1.047.48l2.398 1.045zM13.804 4h-1.133l1.744.698zm.699.828v-.13l2.33.654c.043.011.043.072 0 .084l-1.982.526zm-3.619.479l.697-.698l1.483.654zm2.398.045l-3.27 2.18l4.753-1.526zm2.05 3.053l-5.406-.742l4.185 9.33zm-1.135 8.413l1.221-8.328l.784.96zm-.174.174L9.88 7.749l1.526 9.156zm-2.66-.044L9.837 7.793L7.134 20z");
}

</style>
