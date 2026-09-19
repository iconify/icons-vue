<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrmr0yb6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrmr0yb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:physical-therapy" /></template>
