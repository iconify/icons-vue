<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mqva_v_gi.css';
import '../../css/t/t_13s1fwo.css';
import '../../css/o/o6dcjkbuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mqva_v_gi"/><path class="t_13s1fwo"/><path class="o6dcjkbuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:picture-in-picture-2-duotone" /></template>
