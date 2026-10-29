<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esq-ijbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esq-ijbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:stethoscope-solid" /></template>
