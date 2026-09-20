<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m93qdybrp.css';
import '../../css/y/yu8tkqs3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="m93qdybrp"/><path class="yu8tkqs3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:medium-skin-tone" /></template>
