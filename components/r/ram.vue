<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru7yyeoqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path clip-rule="evenodd" class="ru7yyeoqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:ram" /></template>
