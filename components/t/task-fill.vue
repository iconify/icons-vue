<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrrniwbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrrniwbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:task-fill" /></template>
