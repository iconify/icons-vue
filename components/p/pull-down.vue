<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm1cjwbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="lm1cjwbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:pull-down" /></template>
