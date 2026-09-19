<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwm_4jb1w.css';
import '../../css/j/jmbrci4fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="qwm_4jb1w"/><path class="jmbrci4fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:page-search" /></template>
