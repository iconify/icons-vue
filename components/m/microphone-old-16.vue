<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npn7ripfg.css';
import '../../css/f/fonv89syi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="npn7ripfg"/><path class="fonv89syi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:microphone-old-16" /></template>
