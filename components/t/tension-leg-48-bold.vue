<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5_kp7xga.css';
import '../../css/p/p6gxp-bjt.css';
import '../../css/h/h2w2gxl4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o5_kp7xga"/><path class="p6gxp-bjt"/><path class="h2w2gxl4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tension-leg-48-bold" /></template>
