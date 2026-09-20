<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtk__tbdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtk__tbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tidyverse" /></template>
