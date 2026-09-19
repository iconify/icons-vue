<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvet1dxks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zvet1dxks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:ringer-remove" /></template>
