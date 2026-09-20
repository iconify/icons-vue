<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_qdmlbaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="u_qdmlbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:pause-button" /></template>
