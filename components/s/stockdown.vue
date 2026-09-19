<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyp8xxb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="zyp8xxb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:stockdown" /></template>
