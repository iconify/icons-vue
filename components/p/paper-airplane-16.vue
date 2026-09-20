<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajzldfipa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ajzldfipa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:paper-airplane-16" /></template>
