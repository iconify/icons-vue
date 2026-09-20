<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulj6f9bpb.css';
import '../../css/k/k12cdmnwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulj6f9bpb"/><path class="k12cdmnwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pyth" /></template>
