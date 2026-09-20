<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iis2jirxu.css';
import '../../css/f/fpfbwk8vq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iis2jirxu"/><path class="fpfbwk8vq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:outline" /></template>
