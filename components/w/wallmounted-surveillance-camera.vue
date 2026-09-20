<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk274hgmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nk274hgmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wallmounted-surveillance-camera" /></template>
