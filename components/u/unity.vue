<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb0vnkbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jb0vnkbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:unity" /></template>
