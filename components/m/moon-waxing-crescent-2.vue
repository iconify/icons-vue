<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6vjloltc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="b6vjloltc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-waxing-crescent-2" /></template>
