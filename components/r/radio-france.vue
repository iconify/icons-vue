<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fse-8sbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fse-8sbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:radio-france" /></template>
