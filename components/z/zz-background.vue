<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGfL3SdAcf)" class="r4i437pya"/><path class="armfembvl"/></g><defs><linearGradient id="SVGfL3SdAcf" x1="6.223" x2="16.667" y1="6" y2="19.333" gradientUnits="userSpaceOnUse"><stop class="h_6tp7b_c"/><stop offset="1" class="f3hotyh-n"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zz-background" /></template>
<style>
.armfembvl {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.703 4.089a.7.7 0 0 0-.813.093l-.858.773c-.378.343-.311.978.142 1.218L14.1 9.907l-4.845 3.555a.56.56 0 0 0 .071.951l7.991 4.04l-1.11.805l-9.543-5.356l4.502-3.2a.565.565 0 0 0-.03-.938L8.37 8.067l-.41.613l2.565 1.573l-4.515 3.214a.568.568 0 0 0 .049.946l9.8 5.498c.24.133.533.115.755-.045l1.116-.808a.755.755 0 0 0-.094-1.271l-7.724-3.903l4.844-3.546a.566.566 0 0 0-.062-.947l-7.187-3.88l.854-.773l8.982 4.977l-4.867 3.56a.57.57 0 0 0 .058.947l4.422 2.454l.387-.68l-4.213-2.29l4.866-3.56a.57.57 0 0 0-.057-.946zm-1.12 4.355l.409-.609l-.818-.502l-.369.636l.778.48z");
}

.f3hotyh-n {
  stop-color: var(--svg-color--07a9fc, #07a9fc);
}

.ft5dv1b6b {
  fill: none;
}

.h_6tp7b_c {
  stop-color: var(--svg-color--02eee4, #02eee4);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
