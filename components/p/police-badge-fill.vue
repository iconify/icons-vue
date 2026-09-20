<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmw9xcbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmw9xcbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:police-badge-fill" /></template>
