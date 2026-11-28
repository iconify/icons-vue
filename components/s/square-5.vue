<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2u52mb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2u52mb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:square-5" /></template>
