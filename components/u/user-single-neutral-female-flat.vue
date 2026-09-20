<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5kdnowce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l5kdnowce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:user-single-neutral-female-flat" /></template>
