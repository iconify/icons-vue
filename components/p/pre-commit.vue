<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukg496alp.css';
import '../../css/m/m2xavebym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<rect transform="rotate(-45)" class="ukg496alp"/><path class="m2xavebym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:pre-commit" /></template>
