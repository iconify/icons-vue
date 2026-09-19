<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjk_9gmia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bjk_9gmia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:play" /></template>
