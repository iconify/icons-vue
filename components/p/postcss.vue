<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9hxg7tyk.css';
import '../../css/j/j6cvtntwi.css';
import '../../css/d/d4jypxbqx.css';
import '../../css/a/a7yq0nb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a9hxg7tyk"/><path class="j6cvtntwi"/><path class="d4jypxbqx"/><path class="a7yq0nb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:postcss" /></template>
