<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnjlp6i1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="lnjlp6i1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:volume-3" /></template>
