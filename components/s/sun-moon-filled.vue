<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rudnz8bwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rudnz8bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:sun-moon-filled" /></template>
