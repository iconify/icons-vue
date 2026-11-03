<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_5by1bgh.css';
import '../../css/f/fuuchc-tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="b_5by1bgh"/><path class="fuuchc-tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:pinterest" /></template>
