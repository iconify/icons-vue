<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjcnumbvg.css';
import '../../css/h/h5tf6mlqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjcnumbvg"/><path class="h5tf6mlqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:technology-innovation-institute-falcon" /></template>
