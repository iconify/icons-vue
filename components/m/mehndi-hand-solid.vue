<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v52mwt-ye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v52mwt-ye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mehndi-hand-solid" /></template>
