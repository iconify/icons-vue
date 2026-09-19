<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn3v8nbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="tn3v8nbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:ruler-vertical" /></template>
