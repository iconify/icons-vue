<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9vesdmny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v9vesdmny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:side-panel-close" /></template>
