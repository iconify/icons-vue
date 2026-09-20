<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-7h9_b2g.css';
import '../../css/s/sqhkhzbzv.css';
import '../../css/p/p6_z82b1f.css';
import '../../css/y/ye3osnd_h.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/x/x20hdf3yu.css';
import '../../css/c/ck5-yvb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="c-7h9_b2g"/><path class="sqhkhzbzv"/><circle class="p6_z82b1f"/><path class="ye3osnd_h"/><g class="jn8qy4bru"><path class="x20hdf3yu"/><circle class="ck5-yvb6r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:wind-energy" /></template>
