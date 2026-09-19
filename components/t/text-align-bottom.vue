<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq5xwzb8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dq5xwzb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:text-align-bottom" /></template>
