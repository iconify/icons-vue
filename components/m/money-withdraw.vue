<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu56lfw9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu56lfw9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:money-withdraw" /></template>
