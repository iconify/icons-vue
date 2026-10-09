<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z12cm2qdg.css';
import '../../css/v/v0nouub9y.css';
import '../../css/f/f5n5-__gk.css';
import '../../css/d/dt4en7b0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z12cm2qdg"/><path class="v0nouub9y"/><path class="f5n5-__gk"/><path class="dt4en7b0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:yurt-20" /></template>
