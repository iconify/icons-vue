<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpa7wsbct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpa7wsbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:node-red" /></template>
