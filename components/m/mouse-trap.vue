<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="gk40_xncm"/><path class="fbtg3cb7c"/><path class="cwqfyh2ug"/><path class="qf-2wnnbl"/><ellipse class="br_dmcl0q"/><path class="u7b7ifbmt"/><ellipse class="tbrvzfwxi"/><path class="yc1p7-f6a"/><g class="ug6m59avo"><path class="kd2ch_nyj"/><path class="mekp_4bjx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:mouse-trap" /></template>
<style>
.br_dmcl0q {
  cx: 18.604px;
  cy: 24.424px;
  fill: var(--svg-color--f4900c, #f4900c);
  rx: 1.053px;
  ry: 0.517px;
}

.cwqfyh2ug {
  fill: var(--svg-color--511212, #511212);
  d: path("M12.457 28.073L1.758 12.512h13.13l2.666 4.149z");
}

.fbtg3cb7c {
  fill: var(--svg-color--3d130c, #3d130c);
  d: path("M29.249 28.073H12.457l2.431-15.561h3.291z");
}

.gk40_xncm {
  fill: var(--svg-color--662113, #662113);
  d: path("M24.833.089L0 11.655l12 17.431v.003h18.212L36 16.828z");
}

.kd2ch_nyj {
  d: path("M6.69 13.401h1.583V36H6.69z");
}

.mekp_4bjx {
  d: path("M7.485 12.842a1.58 1.58 0 0 1-1.582-1.582V8.892a.723.723 0 0 0-.73-.73a.73.73 0 0 0-.73.73v2.235c0 .83.343 1.593.885 2.147a3.08 3.08 0 0 0 2.158.885a3.03 3.03 0 0 0 2.579-1.459H8.132a1.6 1.6 0 0 1-.647.142");
}

.qf-2wnnbl {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("m25.608 24.422l-12.364 5.522l.78-1.581c.141.025.269.038.422.038c.69 0 1.266-.301 1.266-.69c0-.339-.46-.615-1.048-.678l1.805-3.665c.602-.19 2.872-.405 5.918.163a.86.86 0 0 0 .55.841a.876.876 0 0 0 1.125-.452c.243.05.473.125.703.213z");
}

.tbrvzfwxi {
  cx: 20.039px;
  cy: 27.023px;
  fill: var(--svg-color--f4900c, #f4900c);
  rx: 2.156px;
  ry: 1.058px;
}

.u7b7ifbmt {
  fill: var(--svg-color--f4900c, #f4900c);
  d: path("M15.716 27.706c0 .389-.574.697-1.27.697c-.15 0-.287-.013-.423-.04l.642-1.327c.586.054 1.051.335 1.051.67m10.097 2.238L13.244 35.09v-1.092c.627 0 1.138-.515 1.138-1.142a1.14 1.14 0 0 0-1.138-1.13v-1.782l12.364-5.522l.077 2.033a1 1 0 0 0-.511-.125c-.639 0-1.151.502-1.151 1.13s.511 1.129 1.151 1.129c.217 0 .422-.063.588-.163z");
}

.ug6m59avo {
  fill: var(--svg-color--f98e00, #f98e00);
}

.yc1p7-f6a {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M18.293 11.655H0L7.562.089h17.271z");
}

</style>
