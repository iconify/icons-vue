<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au6cpbb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="au6cpbb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tag-with-ruble" /></template>
