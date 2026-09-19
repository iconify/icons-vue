<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsdq_3b3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="bsdq_3b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:square-dashed-1" /></template>
