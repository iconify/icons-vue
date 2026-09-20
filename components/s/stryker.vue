<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5m-lqb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5m-lqb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:stryker" /></template>
