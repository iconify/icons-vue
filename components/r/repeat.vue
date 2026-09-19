<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qiu5-accd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qiu5-accd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:repeat" /></template>
