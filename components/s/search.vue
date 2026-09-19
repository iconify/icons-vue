<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3w4gfbgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="n3w4gfbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:search" /></template>
