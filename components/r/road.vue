<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0i69tbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0i69tbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:road" /></template>
