<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv78f1c7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv78f1c7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:triangles-centerline-dashed-horizontal" /></template>
