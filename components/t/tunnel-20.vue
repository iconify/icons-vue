<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f56vf7bck.css';
import '../../css/k/kqal38fxm.css';
import '../../css/p/pycxazbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f56vf7bck"/><path class="kqal38fxm"/><path class="pycxazbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tunnel-20" /></template>
