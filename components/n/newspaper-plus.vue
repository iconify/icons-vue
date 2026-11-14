<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="triitnbik"/><path class="gx24c443j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:newspaper-plus" /></template>
<style>
.gx24c443j {
  d: path("M6.5 7.5h7v4h-7Zm0 7h7m-7 2.5H11m7-2v6m-3-3h6");
}

.triitnbik {
  d: path("M12.2 20H5.5q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182q-.077-.095-.146-.197t-.126-.211t-.105-.221q-.047-.114-.082-.231t-.06-.238q-.024-.121-.036-.243T3 17.5v-12q0-.074.007-.147t.022-.146t.036-.142q.021-.071.049-.139t.063-.133t.076-.126t.087-.119t.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049t.142-.036t.146-.022T4.5 4h11q.074 0 .147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076t.119.087q.057.047.109.099t.099.109t.087.119t.076.126t.063.133t.049.139t.036.142q.015.073.022.146T17 5.5v6.731m4 2.995V9h-4v3.174");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
