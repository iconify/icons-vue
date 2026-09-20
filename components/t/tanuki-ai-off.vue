<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am92l0d3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="am92l0d3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:tanuki-ai-off" /></template>
