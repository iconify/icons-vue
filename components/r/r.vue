<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jof2l9d2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jof2l9d2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:r" /></template>
