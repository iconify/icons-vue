<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymz4q6yty.css';
import '../../css/h/hlfwh4b4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ymz4q6yty"/><path class="hlfwh4b4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:top-arrow" /></template>
