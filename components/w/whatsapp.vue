<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt332n04j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kt332n04j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:whatsapp" /></template>
