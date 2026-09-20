<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvspe7bge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvspe7bge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:navidrome" /></template>
