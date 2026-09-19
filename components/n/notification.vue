<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h68a5vtzz.css';
import '../../css/u/u6i9ewq7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="h68a5vtzz"/><path class="u6i9ewq7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:notification" /></template>
