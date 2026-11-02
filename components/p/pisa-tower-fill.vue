<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftmeqpbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftmeqpbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pisa-tower-fill" /></template>
