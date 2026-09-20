<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9yzp1ixx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l9yzp1ixx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trilium-notes-light" /></template>
