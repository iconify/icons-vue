<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1pmwjlxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1pmwjlxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sorting-center" /></template>
