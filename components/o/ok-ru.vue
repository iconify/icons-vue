<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkr3csbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkr3csbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:ok-ru" /></template>
