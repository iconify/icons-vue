<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqc7ymbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqc7ymbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:strawberry-solid" /></template>
