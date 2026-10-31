<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7uyy1erf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7uyy1erf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-plus-round" /></template>
