<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk0ivzbcg.css';
import '../../css/x/x22kdubov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tk0ivzbcg"/><path class="x22kdubov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:white-paper" /></template>
