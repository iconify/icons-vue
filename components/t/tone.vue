<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th9jinbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th9jinbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:tone" /></template>
