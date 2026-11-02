<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox9f654bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox9f654bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:question-2-fill" /></template>
