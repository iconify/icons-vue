<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esmp9hbxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esmp9hbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:security-camera-alert" /></template>
