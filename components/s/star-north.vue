<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfd20o4wp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfd20o4wp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:star-north" /></template>
