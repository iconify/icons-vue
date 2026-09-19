<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jicomkr5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="jicomkr5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:plus" /></template>
