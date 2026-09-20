<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6flzy-3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j6flzy-3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pencil-bottom-left-to-square-outline" /></template>
