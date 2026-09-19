<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-o3bkbhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-o3bkbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:slack" /></template>
