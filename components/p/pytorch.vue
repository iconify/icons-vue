<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy86frb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zy86frb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:pytorch" /></template>
