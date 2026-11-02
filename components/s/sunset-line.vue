<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev35-acdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev35-acdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sunset-line" /></template>
