<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mld48g7cg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mld48g7cg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:parallel-filled" /></template>
