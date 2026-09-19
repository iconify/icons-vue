<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwy7sxrzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1280};
const content = `<path class="jwy7sxrzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:video-camera" /></template>
