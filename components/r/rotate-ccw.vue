<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwt63lncr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwt63lncr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:rotate-ccw" /></template>
