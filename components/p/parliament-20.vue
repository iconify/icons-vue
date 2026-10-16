<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bizml48vp.css';
import '../../css/r/r-vw3obhe.css';
import '../../css/r/rk9-55a5q.css';
import '../../css/p/pycxazbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bizml48vp"/><path class="r-vw3obhe"/><path class="rk9-55a5q"/><path class="pycxazbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:parliament-20" /></template>
