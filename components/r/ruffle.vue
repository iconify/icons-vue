<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn9l47b1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bn9l47b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ruffle" /></template>
