<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x51ugzbej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x51ugzbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tennis-ball" /></template>
