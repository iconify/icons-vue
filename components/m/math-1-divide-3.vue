<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hklz5bu9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hklz5bu9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:math-1-divide-3" /></template>
