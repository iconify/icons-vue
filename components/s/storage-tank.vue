<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-4boeouc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i-4boeouc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:storage-tank" /></template>
