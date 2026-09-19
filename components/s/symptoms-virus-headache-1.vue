<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej4xkrbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ej4xkrbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:symptoms-virus-headache-1" /></template>
