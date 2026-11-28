<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr4-q2btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yr4-q2btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:toaster-clock" /></template>
