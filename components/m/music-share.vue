<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4t5zg9wy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4t5zg9wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:music-share" /></template>
