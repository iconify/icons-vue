<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e02a5kbah.css';
import '../../css/n/n5nnvotfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":252};
const content = `<path class="e02a5kbah"/><path class="n5nnvotfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mysql-light" /></template>
