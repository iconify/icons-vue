<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co6smrbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="co6smrbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:triangle-stripes" /></template>
