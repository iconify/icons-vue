<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4d0ni6gg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4d0ni6gg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:threedotjs-light" /></template>
