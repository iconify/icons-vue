<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9vx3fbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="h9vx3fbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:x-circle-multiple-light" /></template>
