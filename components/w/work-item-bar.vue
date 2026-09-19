<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsr5subpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="fsr5subpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:work-item-bar" /></template>
