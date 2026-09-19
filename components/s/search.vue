<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq32-81to.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xq32-81to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:search" /></template>
