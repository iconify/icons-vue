<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkxoldbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dkxoldbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:management-outline" /></template>
