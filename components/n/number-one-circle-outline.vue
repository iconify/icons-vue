<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-w8qbchv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-w8qbchv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:number-one-circle-outline" /></template>
