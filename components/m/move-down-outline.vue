<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd4mgibiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vd4mgibiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:move-down-outline" /></template>
