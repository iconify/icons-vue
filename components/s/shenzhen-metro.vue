<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm-aqybfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sm-aqybfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:shenzhen-metro" /></template>
