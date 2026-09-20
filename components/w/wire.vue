<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scc50pnyt.css';
import '../../css/w/wgfto0gvm.css';
import '../../css/i/i0im9gb4o.css';
import '../../css/o/oyapxxb1h.css';
import '../../css/h/h1tlmbc9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="scc50pnyt"/><path class="wgfto0gvm"/><path class="i0im9gb4o"/><path class="oyapxxb1h"/><path class="h1tlmbc9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:wire" /></template>
