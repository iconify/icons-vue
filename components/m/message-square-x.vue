<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwaf-qvuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwaf-qvuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:message-square-x" /></template>
