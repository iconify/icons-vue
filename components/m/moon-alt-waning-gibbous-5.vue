<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro7zm-t0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="ro7zm-t0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-alt-waning-gibbous-5" /></template>
