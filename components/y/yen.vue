<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e79hwtb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="e79hwtb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:yen" /></template>
