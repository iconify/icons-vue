<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ambfcwb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ambfcwb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:stop-filled-alt" /></template>
