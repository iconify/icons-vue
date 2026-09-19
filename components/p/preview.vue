<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkzk0m4_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hkzk0m4_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:preview" /></template>
