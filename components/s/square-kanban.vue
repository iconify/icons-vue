<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrt_0fbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrt_0fbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:square-kanban" /></template>
