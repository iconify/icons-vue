<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfudi9b1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yfudi9b1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:map-16-solid" /></template>
