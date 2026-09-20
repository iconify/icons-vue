<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns20xvbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ns20xvbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:microphone-off" /></template>
