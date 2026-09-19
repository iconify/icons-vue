<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_-xx3b_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="o_-xx3b_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:unknown" /></template>
