<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p73hu3bar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":24};
const content = `<path class="p73hu3bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-speed-1x" /></template>
