<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l03h0hbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l03h0hbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:reset-clock-remix" /></template>
