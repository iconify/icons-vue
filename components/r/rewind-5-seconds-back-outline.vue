<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8thc_b8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o8thc_b8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rewind-5-seconds-back-outline" /></template>
