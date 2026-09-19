<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb1db1bfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="eb1db1bfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:virus-research-alt" /></template>
