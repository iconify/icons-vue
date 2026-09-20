<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olibj9bmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="olibj9bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:rate-stretch-tool-solid" /></template>
