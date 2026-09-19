<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la2sljsfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="la2sljsfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:piano" /></template>
