<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdkpdsawh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdkpdsawh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vivino" /></template>
