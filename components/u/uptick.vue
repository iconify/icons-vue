<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGBXQokdXZ)" class="jqni_vb1p"/><path fill="url(#SVG5GwFpeKT)" class="xow8w5blc"/><path fill="url(#SVGybHffdxi)" class="oxcr7hbnk"/><defs><linearGradient id="SVGBXQokdXZ" x1="13.495" x2="13.495" y1="19.498" y2="9.528" gradientUnits="userSpaceOnUse"><stop/><stop offset=".999" class="v1g637jgr"/></linearGradient><linearGradient id="SVG5GwFpeKT" x1="10.112" x2="10.112" y1="3.258" y2="13.152" gradientUnits="userSpaceOnUse"><stop class="tvpg3zboe"/><stop offset="1" class="wy3so1jkj"/></linearGradient><linearGradient id="SVGybHffdxi" x1="10.659" x2="10.659" y1="3.252" y2="13.195" gradientUnits="userSpaceOnUse"><stop class="tvpg3zboe"/><stop offset="1" class="wy3so1jkj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:uptick" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jqni_vb1p {
  d: path("m13.753 20.953l-3.589-3.7a.15.15 0 0 0-.21-.005l-1.138 1.096a.15.15 0 0 1-.21-.004l-1.573-1.617a.15.15 0 0 1 .005-.21l7.348-7.081a.15.15 0 0 1 .21.004l5.363 5.533a.15.15 0 0 1-.005.21l-5.995 5.779a.14.14 0 0 1-.206-.005m-1.751-5.468l1.81 1.868a.15.15 0 0 0 .211.005l2.324-2.239a.15.15 0 0 0 .005-.21l-1.81-1.868a.15.15 0 0 0-.211-.005l-2.324 2.239a.14.14 0 0 0-.005.21");
}

.oxcr7hbnk {
  d: path("m12.112 4.411l-1.347-1.389a.074.074 0 0 0-.106 0l-1.448 1.39c-.046.045-.014.127.05.127h2.796c.065 0 .101-.082.055-.128");
}

.tvpg3zboe {
  stop-color: var(--svg-color--b927ed, #b927ed);
}

.v1g637jgr {
  stop-color: var(--svg-color--2a005a, #2a005a);
}

.wy3so1jkj {
  stop-color: var(--svg-color--6c06fc, #6c06fc);
}

.xow8w5blc {
  d: path("m14.4 6.983l-4.717 4.541a.15.15 0 0 1-.21-.004L7.661 9.65a.15.15 0 0 1 .004-.21l3.906-3.764a.149.149 0 0 0-.106-.256H8.212a.16.16 0 0 0-.106.041l-4.06 3.915a.15.15 0 0 0-.005.21l5.372 5.537c.055.06.15.06.21.005l6.55-6.314a.15.15 0 0 0 .005-.21L14.61 6.988c-.06-.06-.15-.064-.21-.005");
}

</style>
