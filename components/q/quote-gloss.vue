<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6ucwx1er.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6ucwx1er"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:quote-gloss" /></template>
