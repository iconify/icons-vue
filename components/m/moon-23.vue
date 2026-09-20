<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hiw4zpdte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="hiw4zpdte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-23" /></template>
