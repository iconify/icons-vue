<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhpbuwbuk.css';
import '../../css/o/o8nz3vbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="hhpbuwbuk"/><path class="o8nz3vbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:wrench" /></template>
