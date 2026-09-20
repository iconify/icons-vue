<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drej47b5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="drej47b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:text-flow-rows-solid" /></template>
