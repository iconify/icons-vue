<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu2ir04zv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yu2ir04zv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-minus" /></template>
