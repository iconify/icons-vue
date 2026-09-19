<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt3uzf15z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qt3uzf15z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pills" /></template>
