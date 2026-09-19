<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2ns4mb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x2ns4mb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:question-mark" /></template>
