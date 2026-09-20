<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="rn9janbyj"/><path class="vl7hl_c5b"/><path class="xylq7yb-c"/><path class="yaznc0b_r"/><path class="kh50zbb6d"/><path class="zt3uu2bjo"/><path class="l7n_kib4f"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:moc-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.kh50zbb6d {
  fill: var(--svg-color--3ab1d3, #3ab1d3);
  d: path("M19.5 12c0-2.625-3.235-7-7.5-7s-7.5 3.995-7.5 7a7.5 7.5 0 1 1 15 0");
}

.l7n_kib4f {
  fill: var(--svg-color--ebebeb, #ebebeb);
  d: path("M8.2 11.08V8.5h1.72l1.8 2.955L13.56 8.5h1.75v2.58H17v.67h-1.685v.725H17v.7h-1.685V15.5h-1.55v-4.42l-2.05 2.86l-2-2.86v4.42H8.2v-2.325H6.5v-.7h1.7v-.725H6.5v-.67z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rn9janbyj {
  fill: var(--svg-color--9ce3e5, #9ce3e5);
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.vl7hl_c5b {
  fill: var(--svg-color--4f97a5, #4f97a5);
  d: path("M20 12a8 8 0 0 1-16 0z");
}

.xylq7yb-c {
  fill: var(--svg-color--36c7ce, #36c7ce);
  d: path("M12 19.5a7.5 7.5 0 1 0 0-15a7.5 7.5 0 0 0 0 15");
}

.yaznc0b_r {
  fill: var(--svg-color--359bb1, #359bb1);
  d: path("M12.85 19.95L8.2 15.5l1.62-5.33l1.87 2.12l3.625-3.79L19.94 13a8.3 8.3 0 0 1-1.59 3.885a8.16 8.16 0 0 1-5.5 3.065");
}

.zt3uu2bjo {
  fill: var(--svg-color--28808e, #28808e);
  d: path("M8.385 11.315v-2.58h1.645l1.88 3.085l1.85-3.085h1.74v2.58l1.5-.235l.2.235V12h-1.7v.715l1.495-.235l.2.235v.7H15.5v2.325h-1.535l-.2-.24l.2-4.185l-2.1 2.85l-1.96-2.85v4.425h-1.44L8.2 15.5l.185-2.085h-1.7l-.185-.24l.185-.46h1.7v-.73h-1.7L6.5 11.75l.185-.435z");
}

</style>
