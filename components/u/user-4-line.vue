<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ersehub6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ersehub6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-4-line" /></template>
