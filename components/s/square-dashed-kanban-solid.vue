<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwrwb0bwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwrwb0bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:square-dashed-kanban-solid" /></template>
