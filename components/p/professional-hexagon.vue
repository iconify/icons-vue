<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg8ncpb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zg8ncpb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:professional-hexagon" /></template>
