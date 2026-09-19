<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntry6-bsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ntry6-bsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:package" /></template>
