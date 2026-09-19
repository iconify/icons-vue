<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w07i9qbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="w07i9qbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:rectangle-shape-solid" /></template>
