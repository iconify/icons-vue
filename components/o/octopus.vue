<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1uvocoek.css';
import '../../css/c/cpzoy2bcj.css';
import '../../css/e/ep1f8xb-m.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/b/bes_t3brz.css';
import '../../css/o/ocvinx6xs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="k1uvocoek"/><path class="cpzoy2bcj"/><path class="ep1f8xb-m"/><g class="ij2x_72vy"><path class="bes_t3brz"/><path class="ocvinx6xs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:octopus" /></template>
