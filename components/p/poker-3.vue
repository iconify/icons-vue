<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxh4johuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":17};
const content = `<path class="vxh4johuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:poker-3" /></template>
