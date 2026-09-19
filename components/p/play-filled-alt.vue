<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lempij0ea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lempij0ea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:play-filled-alt" /></template>
