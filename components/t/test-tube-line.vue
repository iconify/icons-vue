<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la79i3b_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la79i3b_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:test-tube-line" /></template>
