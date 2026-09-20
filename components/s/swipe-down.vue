<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmm9ddb9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmm9ddb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:swipe-down" /></template>
