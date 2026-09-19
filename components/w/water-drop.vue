<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgc024btm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgc024btm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:water-drop" /></template>
