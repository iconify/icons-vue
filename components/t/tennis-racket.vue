<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/t/t_ut08bvk.css';
import '../../css/w/wz8qjkb2i.css';
import '../../css/o/o1u583b9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t_ut08bvk"/><path class="wz8qjkb2i"/><circle class="o1u583b9p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:tennis-racket" /></template>
