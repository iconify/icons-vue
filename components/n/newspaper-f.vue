<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qobuiydaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="qobuiydaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:newspaper-f" /></template>
