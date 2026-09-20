<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9ljs0bzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":800,"height":800,"left":100,"top":100};
const content = `<path class="z9ljs0bzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:rollup" /></template>
