<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg3v7v9he.css';
import '../../css/q/qnmhn2udd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yg3v7v9he"/><path class="qnmhn2udd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:nodejs" /></template>
