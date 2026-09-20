<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljb72pblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljb72pblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:user-protection-1" /></template>
