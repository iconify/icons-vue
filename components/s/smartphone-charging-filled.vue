<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv0_5r2xu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fv0_5r2xu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:smartphone-charging-filled" /></template>
