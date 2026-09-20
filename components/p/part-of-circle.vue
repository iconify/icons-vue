<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjx051b5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yjx051b5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:part-of-circle" /></template>
