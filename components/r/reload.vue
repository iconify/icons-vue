<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8xm3vb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j8xm3vb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:reload" /></template>
