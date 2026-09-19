<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix5l_k_we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ix5l_k_we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:monas" /></template>
