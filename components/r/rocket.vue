<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/q6dcbeqzs.css';
import '../../css/q/q0flt88vy.css';
import '../../css/q/qtv77fehd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="q6dcbeqzs"/><path class="q0flt88vy"/><path class="qtv77fehd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:rocket" /></template>
