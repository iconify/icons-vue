<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhc8oxb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhc8oxb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:phone-call-clock" /></template>
