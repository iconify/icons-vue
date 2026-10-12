<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq7mqvbun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fq7mqvbun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:thermometer-sun-filled" /></template>
