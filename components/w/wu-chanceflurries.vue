<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn14cjvwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="yn14cjvwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:wu-chanceflurries" /></template>
