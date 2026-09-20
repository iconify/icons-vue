<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrjl63ncj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nrjl63ncj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:toggle-outline" /></template>
