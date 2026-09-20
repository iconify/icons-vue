<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8mngo21a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r8mngo21a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:search" /></template>
