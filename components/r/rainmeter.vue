<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep44dvl2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ep44dvl2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:rainmeter" /></template>
