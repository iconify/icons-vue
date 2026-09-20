<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn2uuxbep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="cn2uuxbep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-alt-waning-gibbous-1" /></template>
