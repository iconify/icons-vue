<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm9o7dbqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fm9o7dbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-bottom-right-fill-round" /></template>
