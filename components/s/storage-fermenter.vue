<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdjsuka3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vdjsuka3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:storage-fermenter" /></template>
