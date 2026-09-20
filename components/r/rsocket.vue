<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us21q3b7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us21q3b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:rsocket" /></template>
