<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c79_y39oy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c79_y39oy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tired-face-in-circle-outline" /></template>
