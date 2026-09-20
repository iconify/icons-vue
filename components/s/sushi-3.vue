<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzf-akbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vzf-akbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:sushi-3" /></template>
