<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egjrucbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egjrucbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-right-fill-round" /></template>
