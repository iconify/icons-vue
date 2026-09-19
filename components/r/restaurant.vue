<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-0qsbb3u.css';
import '../../css/r/rbtwur1wh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p-0qsbb3u"/><path class="rbtwur1wh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:restaurant" /></template>
