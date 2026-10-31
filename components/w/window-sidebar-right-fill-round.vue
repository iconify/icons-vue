<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r02mcwb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r02mcwb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-sidebar-right-fill-round" /></template>
