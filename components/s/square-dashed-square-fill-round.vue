<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejw8libxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejw8libxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-fill-round" /></template>
