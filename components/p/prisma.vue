<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx3tqmbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx3tqmbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:prisma" /></template>
