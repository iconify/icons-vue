<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwsils6ju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwsils6ju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:yahoo-fill" /></template>
