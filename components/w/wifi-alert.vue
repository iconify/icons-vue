<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt69m96hj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt69m96hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wifi-alert" /></template>
