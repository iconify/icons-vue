<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4wrlib8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4wrlib8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:qodo" /></template>
