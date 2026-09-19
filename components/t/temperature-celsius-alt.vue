<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq6e4izvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xq6e4izvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:temperature-celsius-alt" /></template>
