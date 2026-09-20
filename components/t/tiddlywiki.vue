<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yus__ubvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yus__ubvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tiddlywiki" /></template>
