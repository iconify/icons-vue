<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwy0d1dqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwy0d1dqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:spring-security" /></template>
