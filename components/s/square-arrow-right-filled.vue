<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc-vnabro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sc-vnabro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-arrow-right-filled" /></template>
