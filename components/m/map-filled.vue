<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lymp3m9ab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lymp3m9ab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:map-filled" /></template>
