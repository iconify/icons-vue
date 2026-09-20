<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3wqznb4l.css';
import '../../css/d/d4j9nrbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3wqznb4l"/><path class="d4j9nrbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:nmx" /></template>
