<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni0dax4td.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ni0dax4td"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:signal-medium" /></template>
