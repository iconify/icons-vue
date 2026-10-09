<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-wxw6w6n.css';
import '../../css/c/culelpt1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d-wxw6w6n"/><path class="culelpt1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:taco-20" /></template>
