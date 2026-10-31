<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhfsmufrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhfsmufrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-align-center-round" /></template>
