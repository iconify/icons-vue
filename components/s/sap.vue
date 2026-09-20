<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxr707b_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxr707b_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sap" /></template>
