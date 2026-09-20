<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx0v8cc_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vx0v8cc_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:zorin" /></template>
