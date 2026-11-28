<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7xjmibsi.css';
import '../../css/e/e2rku5b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7xjmibsi secondary"/><path class="e2rku5b-i primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:parallelogram-duo" /></template>
