<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv7b53xgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gv7b53xgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:scatter-diagram-outline" /></template>
