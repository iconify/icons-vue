<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/k5vu_1awm.css';
import '../../css/b/b8muav1zi.css';
import '../../css/u/utnv9fgpg.css';
import '../../css/j/jlzv4qbob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="k5vu_1awm"/><path class="b8muav1zi"/><path class="utnv9fgpg"/><path class="jlzv4qbob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mug-linear" /></template>
