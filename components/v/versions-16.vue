<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv2fgj7zw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tv2fgj7zw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:versions-16" /></template>
