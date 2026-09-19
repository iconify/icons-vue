<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkh4z0b6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vkh4z0b6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:number-small-2" /></template>
