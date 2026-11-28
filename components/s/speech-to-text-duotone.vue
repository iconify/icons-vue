<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j76u6_b3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j76u6_b3z primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:speech-to-text-duotone" /></template>
