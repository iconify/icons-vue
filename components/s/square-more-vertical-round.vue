<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4u7q7bzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4u7q7bzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-more-vertical-round" /></template>
