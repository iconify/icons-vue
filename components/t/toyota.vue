<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvx6p_tap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvx6p_tap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:toyota" /></template>
