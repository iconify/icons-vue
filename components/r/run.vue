<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4d7t7yyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c4d7t7yyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:run" /></template>
