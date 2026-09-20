<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-f7f_xkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-f7f_xkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:phonepe" /></template>
