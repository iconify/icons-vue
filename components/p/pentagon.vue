<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8-16obpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8-16obpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:pentagon" /></template>
