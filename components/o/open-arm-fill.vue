<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5us7hf0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5us7hf0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:open-arm-fill" /></template>
