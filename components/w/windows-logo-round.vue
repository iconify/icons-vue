<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thxt7mbbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thxt7mbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:windows-logo-round" /></template>
