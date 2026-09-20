<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h80y0qbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h80y0qbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:play-card-1" /></template>
