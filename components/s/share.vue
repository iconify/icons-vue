<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j28r0zzbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="j28r0zzbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:share" /></template>
