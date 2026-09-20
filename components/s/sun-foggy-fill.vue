<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/furb690ms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="furb690ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sun-foggy-fill" /></template>
