<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk6fjp9qb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vk6fjp9qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:signal-strength-5" /></template>
