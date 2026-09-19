<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlu_cd69f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="mlu_cd69f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:pills" /></template>
