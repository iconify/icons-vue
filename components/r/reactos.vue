<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu6h-abma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nu6h-abma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:reactos" /></template>
