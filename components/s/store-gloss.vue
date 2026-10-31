<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy76qguez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yy76qguez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:store-gloss" /></template>
