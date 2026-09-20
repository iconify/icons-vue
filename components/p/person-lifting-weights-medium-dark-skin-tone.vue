<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khsi3si7g.css';
import '../../css/v/vf5b9zb0i.css';
import '../../css/y/ym8-nu1-z.css';
import '../../css/o/ol5bs9bwy.css';
import '../../css/x/x8poo_bjf.css';
import '../../css/b/bhez61bon.css';
import '../../css/h/hi3cwbbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="khsi3si7g"/><g class="vf5b9zb0i"><circle class="ym8-nu1-z"/><path class="ol5bs9bwy"/></g><g class="x8poo_bjf"><circle class="ym8-nu1-z"/><path class="bhez61bon"/><path class="hi3cwbbvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:person-lifting-weights-medium-dark-skin-tone" /></template>
