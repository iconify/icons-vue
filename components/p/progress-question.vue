<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whw6_eifb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whw6_eifb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:progress-question" /></template>
