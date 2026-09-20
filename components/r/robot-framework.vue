<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z14493pec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z14493pec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:robot-framework" /></template>
