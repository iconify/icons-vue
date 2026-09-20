<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjr0-jbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qjr0-jbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:triangle-arrow-roadmap-remix" /></template>
