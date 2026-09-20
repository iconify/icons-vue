<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8jlo7bno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8jlo7bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:north-east-circle-line" /></template>
