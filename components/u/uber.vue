<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngt0lm-8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ngt0lm-8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:uber" /></template>
