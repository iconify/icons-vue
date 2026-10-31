<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w19cm5b1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w19cm5b1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ruler-gloss" /></template>
