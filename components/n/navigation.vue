<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-7n0sjuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-7n0sjuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:navigation" /></template>
