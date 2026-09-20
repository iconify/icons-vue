<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c04ix1e3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="c04ix1e3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-16" /></template>
