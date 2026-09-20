<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in3x3jgej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="in3x3jgej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shield-user" /></template>
