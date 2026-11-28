<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_9ku4bcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_9ku4bcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:moon-sparkles-solid" /></template>
