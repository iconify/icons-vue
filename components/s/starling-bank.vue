<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3au2j9yv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3au2j9yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:starling-bank" /></template>
