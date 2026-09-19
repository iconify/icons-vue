<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtgmf5b6d.css';
import '../../css/x/x4ya1hbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qtgmf5b6d"/><path class="x4ya1hbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:scale" /></template>
