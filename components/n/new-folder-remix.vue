<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4h9kcc8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="o4h9kcc8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:new-folder-remix" /></template>
