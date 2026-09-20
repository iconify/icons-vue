<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stev4656k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="stev4656k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:warehouse-pre-outline" /></template>
