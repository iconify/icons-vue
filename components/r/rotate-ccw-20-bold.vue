<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q65t7t7ey.css';
import '../../css/i/iff33zhfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q65t7t7ey"/><path class="iff33zhfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rotate-ccw-20-bold" /></template>
