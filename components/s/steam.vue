<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j48cub3np.css';
import '../../css/b/bg6fy62nr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j48cub3np"/><path class="bg6fy62nr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:steam" /></template>
