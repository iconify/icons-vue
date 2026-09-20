<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcgb2zbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcgb2zbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vestel" /></template>
