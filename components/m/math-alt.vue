<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxw40mb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxw40mb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:math-alt" /></template>
