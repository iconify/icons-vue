<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6-_lr_vw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l6-_lr_vw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:skill-level-basic" /></template>
