<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/x_bc36b2h.css';
import '../../css/o/oco87xb9u.css';
import '../../css/v/vr45wkbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="x_bc36b2h"/><path class="oco87xb9u"/><path class="vr45wkbit"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:people-cross" /></template>
