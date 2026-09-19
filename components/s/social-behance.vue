<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jqs4cdc7m.css';
import '../../css/s/sq7tt6u1i.css';
import '../../css/o/ozlgx6bya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<g class="cuyn6tgcc"><path class="jqs4cdc7m"/><path class="sq7tt6u1i"/><path class="ozlgx6bya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-behance" /></template>
