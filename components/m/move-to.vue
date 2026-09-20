<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk2y--wzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="bk2y--wzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:move-to" /></template>
