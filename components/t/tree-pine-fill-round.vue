<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prbyuccsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prbyuccsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tree-pine-fill-round" /></template>
