<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy1w_4b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zy1w_4b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mobile-upload-corner-fill-round" /></template>
