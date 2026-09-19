<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es10opblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":24};
const content = `<path class="es10opblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:pinterest" /></template>
