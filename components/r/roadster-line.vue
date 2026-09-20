<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzymo3a0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzymo3a0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:roadster-line" /></template>
