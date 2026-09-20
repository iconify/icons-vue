<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-pxa7trs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-pxa7trs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:refresh-sharp" /></template>
