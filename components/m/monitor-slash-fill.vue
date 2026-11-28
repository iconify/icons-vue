<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6lmx-t-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="i6lmx-t-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:monitor-slash-fill" /></template>
