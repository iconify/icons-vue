<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f25ju-b2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="f25ju-b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:wmo4680-02" /></template>
