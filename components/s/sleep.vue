<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2b_tlbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h2b_tlbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:sleep" /></template>
