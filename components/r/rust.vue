<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy2m2ubdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wy2m2ubdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:rust" /></template>
