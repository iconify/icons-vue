<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpky_m6mv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rpky_m6mv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:play" /></template>
