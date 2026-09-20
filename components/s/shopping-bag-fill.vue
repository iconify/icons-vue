<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw-n8ebic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fw-n8ebic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shopping-bag-fill" /></template>
