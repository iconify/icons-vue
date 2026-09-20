<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1f2s3uas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v1f2s3uas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:thermometer-positive-remix" /></template>
