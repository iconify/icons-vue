<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc9wrxdmw.css';
import '../../css/d/dz7d0mbwh.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d2kvgvbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVGtdziAeMj" class="bc9wrxdmw"/><path id="SVGZ6VuEeVE" class="dz7d0mbwh"/></defs><g class="cuyn6tgcc"><use href="#SVGtdziAeMj"/><use href="#SVGZ6VuEeVE" clip-rule="evenodd" class="d2kvgvbvc"/><use href="#SVGtdziAeMj"/><use href="#SVGZ6VuEeVE" clip-rule="evenodd" class="d2kvgvbvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:physical-therapy" /></template>
