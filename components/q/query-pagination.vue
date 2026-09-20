<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6w3d1k8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="d6w3d1k8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:query-pagination" /></template>
