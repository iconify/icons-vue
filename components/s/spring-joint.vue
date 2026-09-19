<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja56ooacg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ja56ooacg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:spring-joint" /></template>
