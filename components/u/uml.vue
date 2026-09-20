<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfpo1o8mc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfpo1o8mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:uml" /></template>
