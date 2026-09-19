<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1qr2z6ci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="reorder-outline"><path class="Vector o1qr2z6ci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:reorder-outline" /></template>
