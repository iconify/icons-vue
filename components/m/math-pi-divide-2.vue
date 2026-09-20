<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r86_r3bnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r86_r3bnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:math-pi-divide-2" /></template>
