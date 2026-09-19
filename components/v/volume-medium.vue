<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-6wdt8ra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="f-6wdt8ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:volume-medium" /></template>
