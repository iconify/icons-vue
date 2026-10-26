<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1k2lkb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path clip-rule="evenodd" class="y1k2lkb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:rallly" /></template>
