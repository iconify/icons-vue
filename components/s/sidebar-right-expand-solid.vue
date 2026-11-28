<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6y21mb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6y21mb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sidebar-right-expand-solid" /></template>
