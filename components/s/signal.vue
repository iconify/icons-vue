<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edm8_0bze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edm8_0bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:signal" /></template>
