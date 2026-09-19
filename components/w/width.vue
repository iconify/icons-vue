<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzatv2dyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzatv2dyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:width" /></template>
