<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voc11hbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="voc11hbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:stable" /></template>
