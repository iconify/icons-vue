<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0cbo8bvk.css';
import '../../css/f/fd4fpfb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="x0cbo8bvk"/><path class="fd4fpfb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:page-pdf" /></template>
