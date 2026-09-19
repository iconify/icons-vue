<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn48d1adx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1632,"height":1792};
const content = `<path class="jn48d1adx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:sort-alpha-desc" /></template>
