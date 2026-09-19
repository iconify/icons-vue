<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn4l59wgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qn4l59wgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:sort-alpha-asc" /></template>
