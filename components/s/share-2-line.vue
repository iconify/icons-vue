<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws4ge5kmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ws4ge5kmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:share-2-line" /></template>
