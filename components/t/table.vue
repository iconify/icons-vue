<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urcr01bii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urcr01bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:table" /></template>
