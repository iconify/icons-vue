<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d457f5bbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":24};
const content = `<path class="d457f5bbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-speed-0-8x" /></template>
