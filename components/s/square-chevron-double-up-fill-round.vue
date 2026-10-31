<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e39-0ub8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e39-0ub8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-chevron-double-up-fill-round" /></template>
