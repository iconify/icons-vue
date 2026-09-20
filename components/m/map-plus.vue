<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz85g5bvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz85g5bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:map-plus" /></template>
