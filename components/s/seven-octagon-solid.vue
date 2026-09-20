<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foumo_b3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="foumo_b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:seven-octagon-solid" /></template>
