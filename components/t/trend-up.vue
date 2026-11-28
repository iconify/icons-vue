<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8en98bkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8en98bkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:trend-up" /></template>
