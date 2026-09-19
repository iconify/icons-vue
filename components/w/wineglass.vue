<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnpts2biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="xnpts2biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:wineglass" /></template>
