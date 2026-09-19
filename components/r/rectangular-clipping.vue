<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmjcyj3vp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="vmjcyj3vp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:rectangular-clipping" /></template>
