<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":342};
const content = `<defs><linearGradient id="SVGCdghnblF" x1="42.593%" x2="57.245%" y1="0%" y2="93.174%"><stop offset="0%" class="o19ptqc3p"/><stop offset="100%" class="cequoob6b"/></linearGradient><linearGradient id="SVG5tapKdof" x1="40.122%" x2="62.028%" y1="0%" y2="95.592%"><stop offset="0%" class="hn2esfblp"/><stop offset="100%" class="o19ptqc3p"/></linearGradient><linearGradient id="SVGRvjwscVp" x1="27.774%" x2="55.012%" y1="0%" y2="96.828%"><stop offset="0%" class="lgwa88bup"/><stop offset="100%" class="hn2esfblp"/></linearGradient><path id="SVGvAvgNc4T" class="wo7z-db0r"/></defs><mask id="SVGvCV5wclL" class="n1mjunbsu"><use href="#SVGvAvgNc4T"/></mask><path fill="url(#SVGCdghnblF)" mask="url(#SVGvCV5wclL)" class="m-wkatwhp"/><path mask="url(#SVGvCV5wclL)" class="ks673kbvq"/><path mask="url(#SVGvCV5wclL)" class="jrnb9rbxf"/><path fill="url(#SVG5tapKdof)" mask="url(#SVGvCV5wclL)" class="f-u_5f80v"/><path fill="url(#SVGRvjwscVp)" mask="url(#SVGvCV5wclL)" class="hef0a4b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:microsoft-power-bi" /></template>
<style>
.cequoob6b {
  stop-color: var(--svg-color--c87e0e, #c87e0e);
}

.f-u_5f80v {
  d: path("M184.889 99.556v241.777H71.11v-256h99.556c7.854 0 14.222 6.368 14.222 14.223");
}

.hef0a4b3n {
  d: path("M0 170.667v170.666h113.778V184.89c0-7.855-6.368-14.222-14.222-14.222z");
}

.hn2esfblp {
  stop-color: var(--svg-color--f6d751, #f6d751);
}

.jrnb9rbxf {
  fill-opacity: var(--svg-fill-opacity--0-18, 0.18);
  d: path("M184.889 106.667v241.777H71.11v-256h99.556c7.854 0 14.222 6.368 14.222 14.223");
}

.ks673kbvq {
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M184.889 100.978v241.778H71.11v-256h99.556c7.854 0 14.222 6.367 14.222 14.222");
}

.lgwa88bup {
  stop-color: var(--svg-color--f9e589, #f9e589);
}

.m-wkatwhp {
  d: path("M256 0v341.333H142.222V0z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.o19ptqc3p {
  stop-color: var(--svg-color--e6ad10, #e6ad10);
}

.wo7z-db0r {
  d: path("M142.222 14.222C142.222 6.368 148.59 0 156.444 0h85.334C249.632 0 256 6.368 256 14.222v312.89c0 7.854-6.368 14.221-14.222 14.221H14.222C6.368 341.333 0 334.966 0 327.111V184.89c0-7.855 6.368-14.222 14.222-14.222h56.89V99.556c0-7.855 6.367-14.223 14.222-14.223h56.888z");
}

</style>
