<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqnpa1bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eqnpa1bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:video-camera-symbol" /></template>
