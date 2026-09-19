<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc7v3q69r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dc7v3q69r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:rewind-one-x" /></template>
