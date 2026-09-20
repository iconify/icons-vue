<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxu427bvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fxu427bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:raphael" /></template>
