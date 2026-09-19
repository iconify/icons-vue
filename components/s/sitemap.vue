<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgy167gpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="rgy167gpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:sitemap" /></template>
