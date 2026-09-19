<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt7l2dbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="qt7l2dbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:proj-stereo" /></template>
