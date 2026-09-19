<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8vkeubrv.css';
import '../../css/k/k18o02rhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q8vkeubrv"/><path class="k18o02rhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:wallet" /></template>
