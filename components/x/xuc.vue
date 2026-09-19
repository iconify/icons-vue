<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqo0fw7ui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xqo0fw7ui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:xuc" /></template>
