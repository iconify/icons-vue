<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzjxf3r3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="uzjxf3r3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:payment-card" /></template>
