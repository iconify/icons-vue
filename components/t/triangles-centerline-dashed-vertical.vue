<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z98wpl-ew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z98wpl-ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:triangles-centerline-dashed-vertical" /></template>
