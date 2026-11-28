<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0t8p3g6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0t8p3g6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:plug-check" /></template>
