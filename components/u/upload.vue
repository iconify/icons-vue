<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua9keqbpv.css';
import '../../css/n/nz_20wbpz.css';
import '../../css/e/e7pn7ylvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<mask id="SVGJjBfxcFL" width="48" height="48" x="0" y="0" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="ua9keqbpv"/></mask><g mask="url(#SVGJjBfxcFL)" class="nz_20wbpz"><path class="e7pn7ylvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:upload" /></template>
