<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9pq-abme.css';
import '../../css/h/hz1zk_bsj.css';
import '../../css/a/awpu8mb-l.css';
import '../../css/x/x8poo_bjf.css';
import '../../css/n/n5bhdb4ld.css';
import '../../css/m/mzz-ioa3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<g class="k9pq-abme"><circle class="hz1zk_bsj"/><path class="awpu8mb-l"/></g><g class="x8poo_bjf"><circle class="hz1zk_bsj"/><path class="n5bhdb4ld"/><path class="mzz-ioa3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:person-in-lotus-position-medium-skin-tone" /></template>
