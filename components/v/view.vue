<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjsu38yxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="sjsu38yxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:view" /></template>
