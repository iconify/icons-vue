<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8sz2mb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8sz2mb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:square-kanban-plus" /></template>
