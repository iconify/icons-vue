<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os9ln895c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="os9ln895c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:steps-number-remix" /></template>
