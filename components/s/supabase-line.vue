<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjm6bftui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjm6bftui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:supabase-line" /></template>
