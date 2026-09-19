<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_o20eohb.css';
import '../../css/f/f23s2bc5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="p_o20eohb"/><path class="f23s2bc5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:view-filled" /></template>
