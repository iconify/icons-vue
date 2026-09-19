<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foj66g2rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="foj66g2rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:quarter-circle" /></template>
