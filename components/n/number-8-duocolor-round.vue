<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr5p_h15c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nr5p_h15c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:number-8-duocolor-round" /></template>
