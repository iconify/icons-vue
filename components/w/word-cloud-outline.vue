<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhqb61bvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yhqb61bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:word-cloud-outline" /></template>
