<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gds9jyqsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gds9jyqsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:qantas" /></template>
