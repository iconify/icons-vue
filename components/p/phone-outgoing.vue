<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggljjvbkh.css';
import '../../css/s/s0ff9zwpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ggljjvbkh"/><path class="s0ff9zwpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:phone-outgoing" /></template>
