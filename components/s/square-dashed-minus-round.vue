<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sds54fboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sds54fboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-minus-round" /></template>
