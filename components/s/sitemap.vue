<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g82h75bir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1536};
const content = `<path class="g82h75bir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:sitemap" /></template>
