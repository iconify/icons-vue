<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9g0b5k5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="c9g0b5k5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:spring-14" /></template>
