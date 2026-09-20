<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs15pq7xi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xs15pq7xi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:plugin-line" /></template>
