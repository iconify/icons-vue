<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo2z8_zoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo2z8_zoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:milk-gloss" /></template>
