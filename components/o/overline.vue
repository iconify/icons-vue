<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqfyldb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqfyldb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:overline" /></template>
