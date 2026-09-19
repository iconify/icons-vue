<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytkl7iroe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ytkl7iroe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:question" /></template>
