<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpmfjeb8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zpmfjeb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:user-tie" /></template>
