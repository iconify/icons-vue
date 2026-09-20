<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idjro8bwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="idjro8bwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:unlink-outline" /></template>
