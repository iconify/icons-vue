<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zntwc7g4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zntwc7g4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:pause-16" /></template>
