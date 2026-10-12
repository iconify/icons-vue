<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co2y78wts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="co2y78wts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:parking-meter-filled" /></template>
