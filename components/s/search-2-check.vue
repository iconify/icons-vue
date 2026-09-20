<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y90iic0su.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y90iic0su"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-2-check" /></template>
