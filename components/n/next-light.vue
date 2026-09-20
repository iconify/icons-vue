<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqlswxbhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wqlswxbhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:next-light" /></template>
