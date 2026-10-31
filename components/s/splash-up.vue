<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc3w75-_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dc3w75-_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:splash-up" /></template>
