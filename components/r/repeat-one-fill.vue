<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk0a1hbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk0a1hbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:repeat-one-fill" /></template>
