<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsg-1ghgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lsg-1ghgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:surface-top-outline" /></template>
