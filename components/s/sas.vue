<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjmigcbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":6.35,"height":6.35};
const content = `<path class="cjmigcbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:sas" /></template>
