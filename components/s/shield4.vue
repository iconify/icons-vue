<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3ues5odh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3ues5odh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:shield4" /></template>
