<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt8f97bci.css';
import '../../css/x/xyx_nmb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qt8f97bci"/><path class="xyx_nmb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pound-20-bold" /></template>
