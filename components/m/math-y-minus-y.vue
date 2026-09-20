<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i84mfemjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i84mfemjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:math-y-minus-y" /></template>
