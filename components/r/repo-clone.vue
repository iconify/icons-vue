<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wocea_14z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wocea_14z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:repo-clone" /></template>
