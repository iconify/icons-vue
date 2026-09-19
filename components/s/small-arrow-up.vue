<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/toakrhjlf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":380,"height":700};
const content = `<path class="toakrhjlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:small-arrow-up" /></template>
