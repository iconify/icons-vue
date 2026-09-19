<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amb5sjbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1536};
const content = `<path class="amb5sjbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:window-close-o" /></template>
