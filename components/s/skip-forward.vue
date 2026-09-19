<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg5963bfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qg5963bfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:skip-forward" /></template>
