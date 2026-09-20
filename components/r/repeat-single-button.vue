<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8otfzbxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="q8otfzbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:repeat-single-button" /></template>
