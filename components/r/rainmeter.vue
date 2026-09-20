<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd5kt62js.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd5kt62js"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:rainmeter" /></template>
