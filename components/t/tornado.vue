<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipv2fhbkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipv2fhbkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:tornado" /></template>
