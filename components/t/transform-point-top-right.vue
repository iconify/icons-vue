<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/p/pq55qvb7b.css';
import '../../css/k/k5p2vccgg.css';
import '../../css/g/gt2lf583p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pq55qvb7b"/><path class="k5p2vccgg"/><path class="gt2lf583p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:transform-point-top-right" /></template>
