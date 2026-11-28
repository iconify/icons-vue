<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrhzudmjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrhzudmjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:scissors" /></template>
