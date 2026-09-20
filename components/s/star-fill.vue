<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vczweh8xk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vczweh8xk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:star-fill" /></template>
