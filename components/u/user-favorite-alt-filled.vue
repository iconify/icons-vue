<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj49dybyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jj49dybyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user-favorite-alt-filled" /></template>
