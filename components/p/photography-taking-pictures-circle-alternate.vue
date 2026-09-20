<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezcxgba8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ezcxgba8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:photography-taking-pictures-circle-alternate" /></template>
