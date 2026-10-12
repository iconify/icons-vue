<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us-3nabvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us-3nabvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:spray-can-filled" /></template>
