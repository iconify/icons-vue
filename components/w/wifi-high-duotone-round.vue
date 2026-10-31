<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smw7abbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smw7abbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wifi-high-duotone-round" /></template>
