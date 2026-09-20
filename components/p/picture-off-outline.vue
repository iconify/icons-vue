<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vugj7860w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vugj7860w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:picture-off-outline" /></template>
