<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz2soiqdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz2soiqdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:remedy-entertainment" /></template>
