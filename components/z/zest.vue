<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va-kg5ifn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="va-kg5ifn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:zest" /></template>
