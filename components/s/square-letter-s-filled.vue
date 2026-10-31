<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1p_b8b0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w1p_b8b0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-letter-s-filled" /></template>
