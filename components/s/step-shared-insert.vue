<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddz2_obsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ddz2_obsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:step-shared-insert" /></template>
