<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6l54sb0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z6l54sb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:receipt-turkish-lira-filled" /></template>
