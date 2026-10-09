<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gro8lebrz.css';
import '../../css/c/c6_bjubqo.css';
import '../../css/d/d50-4zb9n.css';
import '../../css/r/rkepvhbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gro8lebrz"/><path class="c6_bjubqo"/><path class="d50-4zb9n"/><path class="rkepvhbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mvhr-20-bold" /></template>
