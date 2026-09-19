<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djo92_bmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="djo92_bmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:unlock2-fill" /></template>
