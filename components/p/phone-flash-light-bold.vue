<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r41gwzhxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r41gwzhxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:phone-flash-light-bold" /></template>
