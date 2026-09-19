<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2l5ukbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2l5ukbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:shop" /></template>
