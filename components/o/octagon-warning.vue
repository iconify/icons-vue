<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqolydbpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqolydbpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:octagon-warning" /></template>
