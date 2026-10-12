<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lljs6_q0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lljs6_q0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:star-half-filled" /></template>
