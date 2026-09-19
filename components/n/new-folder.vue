<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i14aqqblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i14aqqblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:new-folder" /></template>
