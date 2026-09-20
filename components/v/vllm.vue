<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dixa9hblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dixa9hblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:vllm" /></template>
