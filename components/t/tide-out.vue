<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuyr6obnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fuyr6obnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tide-out" /></template>
