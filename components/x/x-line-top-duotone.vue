<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1y_t4b6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1y_t4b6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:x-line-top-duotone" /></template>
