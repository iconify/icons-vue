<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g96qynbtf.css';
import '../../css/y/yqg61wbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g96qynbtf"/><path class="yqg61wbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:reactor-20" /></template>
