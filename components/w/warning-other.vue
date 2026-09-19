<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxj_3jtzx.css';
import '../../css/t/t18caz0-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fxj_3jtzx"/><path class="t18caz0-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:warning-other" /></template>
