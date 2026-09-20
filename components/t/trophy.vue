<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2d9a-f-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d2d9a-f-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:trophy" /></template>
