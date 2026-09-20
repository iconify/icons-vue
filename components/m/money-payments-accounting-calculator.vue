<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c22bshnsy.css';
import '../../css/j/j0hahwblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c22bshnsy"/><path class="j0hahwblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:money-payments-accounting-calculator" /></template>
