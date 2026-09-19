<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcw41v1xo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="wcw41v1xo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:view-list-tree" /></template>
