<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp6t8obxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tp6t8obxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:voicemail-fill-round" /></template>
