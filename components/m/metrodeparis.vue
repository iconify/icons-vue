<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv9eo3bwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vv9eo3bwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:metrodeparis" /></template>
