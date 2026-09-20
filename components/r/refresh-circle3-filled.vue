<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjv321_of.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjv321_of"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:refresh-circle3-filled" /></template>
