<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps22e6bmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps22e6bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shower-line" /></template>
