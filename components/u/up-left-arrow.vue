<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qscg1vb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qscg1vb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:up-left-arrow" /></template>
