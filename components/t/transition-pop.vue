<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_s32wagp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="p_s32wagp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:transition-pop" /></template>
