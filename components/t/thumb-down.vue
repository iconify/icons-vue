<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfg6x-0ty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfg6x-0ty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:thumb-down" /></template>
