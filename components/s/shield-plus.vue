<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyi5cjxdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="qyi5cjxdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:shield-plus" /></template>
