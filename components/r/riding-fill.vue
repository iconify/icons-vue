<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0lp7qnap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0lp7qnap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:riding-fill" /></template>
