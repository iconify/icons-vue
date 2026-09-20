<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywy6t0bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywy6t0bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:math-greater" /></template>
