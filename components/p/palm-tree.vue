<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ziv56acgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ziv56acgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:palm-tree" /></template>
