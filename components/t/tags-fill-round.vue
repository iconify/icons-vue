<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6-ys596e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6-ys596e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tags-fill-round" /></template>
