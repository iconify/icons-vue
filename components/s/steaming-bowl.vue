<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mad9vde-d.css';
import '../../css/m/my9e3dkzb.css';
import '../../css/r/rpvb-o6bq.css';
import '../../css/t/tys-riorg.css';
import '../../css/p/plip7obcr.css';
import '../../css/r/rit23ppab.css';
import '../../css/u/u6xpit2om.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<defs><path id="SVGNItmzdJR" class="mad9vde-d"/></defs><path class="my9e3dkzb"/><g class="rpvb-o6bq"><path class="tys-riorg"/><use href="#SVGNItmzdJR" class="plip7obcr"/><path class="rit23ppab"/></g><use href="#SVGNItmzdJR" class="u6xpit2om"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:steaming-bowl" /></template>
