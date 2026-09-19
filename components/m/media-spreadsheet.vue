<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv3eiyb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qv3eiyb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:media-spreadsheet" /></template>
