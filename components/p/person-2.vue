<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asuv-oy1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="asuv-oy1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:person-2" /></template>
