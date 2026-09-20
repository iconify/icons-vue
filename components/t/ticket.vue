<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/ugq19dr1m.css';
import '../../css/e/evvg3r27v.css';
import '../../css/c/c9vb-8b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ugq19dr1m"/><path class="evvg3r27v"/><path class="c9vb-8b2l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:ticket" /></template>
