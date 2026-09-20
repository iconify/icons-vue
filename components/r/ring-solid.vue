<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvjmr5nlz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wvjmr5nlz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:ring-solid" /></template>
