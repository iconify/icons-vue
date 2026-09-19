<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w2lm7d1fb.css';
import '../../css/p/plxuwnb-i.css';
import '../../css/t/tioa-udgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="w2lm7d1fb"/><path class="plxuwnb-i"/><path class="tioa-udgt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:volume-up-fill" /></template>
