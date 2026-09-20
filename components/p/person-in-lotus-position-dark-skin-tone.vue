<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_raf5bng.css';
import '../../css/h/hz1zk_bsj.css';
import '../../css/a/awpu8mb-l.css';
import '../../css/x/x8poo_bjf.css';
import '../../css/n/n5bhdb4ld.css';
import '../../css/m/mzz-ioa3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<g class="e_raf5bng"><circle class="hz1zk_bsj"/><path class="awpu8mb-l"/></g><g class="x8poo_bjf"><circle class="hz1zk_bsj"/><path class="n5bhdb4ld"/><path class="mzz-ioa3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:person-in-lotus-position-dark-skin-tone" /></template>
