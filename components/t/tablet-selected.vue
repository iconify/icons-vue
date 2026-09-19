<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en1hy5blk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="en1hy5blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:tablet-selected" /></template>
