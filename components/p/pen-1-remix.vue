<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3j5t0b4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m3j5t0b4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:pen-1-remix" /></template>
