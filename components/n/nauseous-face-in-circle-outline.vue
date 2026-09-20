<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh1supfsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zh1supfsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:nauseous-face-in-circle-outline" /></template>
