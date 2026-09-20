<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv471dbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dv471dbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:moneygram" /></template>
