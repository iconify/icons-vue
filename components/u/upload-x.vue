<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhuzsw-1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhuzsw-1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:upload-x" /></template>
