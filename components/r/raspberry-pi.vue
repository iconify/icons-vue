<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr960vbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr960vbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:raspberry-pi" /></template>
