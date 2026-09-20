<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8q52ackl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8q52ackl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:proton-calendar" /></template>
