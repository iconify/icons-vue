<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu68e7-kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eu68e7-kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:row-vertical-filled" /></template>
