<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se0z4cciz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se0z4cciz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:one-finger-short-tap" /></template>
