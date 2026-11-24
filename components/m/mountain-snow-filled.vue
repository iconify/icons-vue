<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg2ulzb4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tg2ulzb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mountain-snow-filled" /></template>
