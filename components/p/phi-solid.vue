<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjqn1y8dg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjqn1y8dg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:phi-solid" /></template>
