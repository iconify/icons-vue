<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-y-j6fsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="f-y-j6fsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:transition-effect" /></template>
