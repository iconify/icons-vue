<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_32mb0cg.css';
import '../../css/q/qsse9abge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="q_32mb0cg"/><path class="qsse9abge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:rstudio" /></template>
