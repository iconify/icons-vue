<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m14lmibdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1411,"height":1557};
const content = `<path class="m14lmibdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ubs-etracs-dark" /></template>
