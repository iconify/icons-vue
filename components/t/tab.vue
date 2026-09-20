<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp84et6rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp84et6rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:tab" /></template>
