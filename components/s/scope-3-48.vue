<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0b5pxbkr.css';
import '../../css/w/wj_mk056d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j0b5pxbkr"/><path class="wj_mk056d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scope-3-48" /></template>
