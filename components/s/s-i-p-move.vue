<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq26b0qdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="gq26b0qdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:s-i-p-move" /></template>
