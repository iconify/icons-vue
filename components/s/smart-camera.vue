<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-7yccbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-7yccbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:smart-camera" /></template>
