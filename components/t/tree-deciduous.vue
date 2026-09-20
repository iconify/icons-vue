<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzqcv5bxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzqcv5bxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:tree-deciduous" /></template>
