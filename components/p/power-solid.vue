<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuzz96_1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuzz96_1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:power-solid" /></template>
