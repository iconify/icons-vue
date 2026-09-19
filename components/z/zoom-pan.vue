<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1ol51blr.css';
import '../../css/y/yzhyb8bwk.css';
import '../../css/p/p18cy_m8i.css';
import '../../css/l/lj5rkfb6q.css';
import '../../css/q/qy_260b7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a1ol51blr"/><path class="yzhyb8bwk"/><path class="p18cy_m8i"/><path class="lj5rkfb6q"/><path class="qy_260b7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:zoom-pan" /></template>
