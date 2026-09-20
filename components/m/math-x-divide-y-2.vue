<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7ahtgoqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7ahtgoqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:math-x-divide-y-2" /></template>
