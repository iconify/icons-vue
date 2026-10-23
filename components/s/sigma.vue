<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7kmugprb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7kmugprb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:sigma" /></template>
