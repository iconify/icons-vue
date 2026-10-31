<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf1b6zb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bf1b6zb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:upload-gloss" /></template>
