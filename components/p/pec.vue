<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGEoDrfQFe)" class="kz425hb-l"/><path fill="url(#SVG3aEHNceO)" class="ifgbtacmt"/><path clip-rule="evenodd" class="a44-kjn4k"/><defs><linearGradient id="SVGEoDrfQFe" x1="12" x2="7.45" y1="21" y2="11.698" gradientUnits="userSpaceOnUse"><stop class="nwsvd6okn"/><stop offset=".6" class="hz4x16brj"/><stop offset=".81" class="n6rxn4bpf"/><stop offset="1" class="dxush8e4e"/></linearGradient><linearGradient id="SVG3aEHNceO" x1="16.511" x2="8.939" y1="12" y2="6.199" gradientUnits="userSpaceOnUse"><stop class="pyixrd61h"/><stop offset=".5" class="jpgaiziuj"/><stop offset="1" class="asyrkjbah"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pec" /></template>
<style>
.a44-kjn4k {
  fill: var(--svg-color--81a1ee, #81a1ee);
  fill-rule: evenodd;
  d: path("M13.092 3C6.426 5.299 5 9.117 5 9.117V7.18C5 4.872 6.836 3 9.102 3z");
}

.asyrkjbah {
  stop-color: var(--svg-color--cfddff, #cfddff);
}

.dxush8e4e {
  stop-color: var(--svg-color--1a3fba, #1a3fba);
}

.ft5dv1b6b {
  fill: none;
}

.hz4x16brj {
  stop-color: var(--svg-color--6f90e5, #6f90e5);
}

.ifgbtacmt {
  d: path("M19 8.088c0 2.06-1.47 3.813-3.465 4.136l-7.567 1.223C6.284 13.705 5 14.823 5 16.52V7.09l.002-.032L5 7.181v1.936S6.426 5.3 13.091 3h1.273a4.6 4.6 0 0 1 3.278 1.384A4.77 4.77 0 0 1 19 7.725z");
}

.jpgaiziuj {
  stop-color: var(--svg-color--afc5fb, #afc5fb);
}

.kz425hb-l {
  d: path("M12.69 18.131C12.286 19.816 10.805 21 9.103 21C6.837 21 5 19.128 5 16.82v-.3c0-1.697 1.284-2.815 2.968-3.073l6.087-.985z");
}

.n6rxn4bpf {
  stop-color: var(--svg-color--4568d0, #4568d0);
}

.nwsvd6okn {
  stop-color: var(--svg-color--81a1ee, #81a1ee);
}

.pyixrd61h {
  stop-color: var(--svg-color--a4bdfa, #a4bdfa);
}

</style>
