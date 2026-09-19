<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cury92biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":24};
const content = `<path class="cury92biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:visa" /></template>
