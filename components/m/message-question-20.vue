<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzs5177np.css';
import '../../css/n/non1cd9gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fzs5177np"/><path class="non1cd9gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-question-20" /></template>
