<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-oew8b_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-oew8b_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:option-duotone-round" /></template>
