<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6m20abim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6m20abim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:mcafee-logo-bold" /></template>
