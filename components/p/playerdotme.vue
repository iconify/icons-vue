<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q82i5zb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q82i5zb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:playerdotme" /></template>
