<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uu8qzcbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:no-plastic-bags" /></template>
<style>
.uu8qzcbzm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.4 3.5h1.1v1.1m4.695 4.69q.125-.046.247-.101t.239-.119q.118-.065.23-.138t.218-.154t.206-.171t.192-.185q.093-.097.178-.2t.161-.213q.077-.11.145-.225t.128-.235q.059-.12.109-.244t.09-.252t.07-.258t.051-.262t.031-.266q.01-.133.01-.267V3.5H19v11.585m-1.983 5.861Q16.761 21 16.5 21h-9q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182t-.146-.197t-.126-.211t-.105-.221q-.047-.114-.082-.231t-.06-.238t-.036-.243T5 18.5V8.969M3.5 3.5l17 17");
}

</style>
