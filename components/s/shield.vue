<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy7gb0z0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="oy7gb0z0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:shield" /></template>
