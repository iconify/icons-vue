<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol0zcy-5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ol0zcy-5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:map-pin-pen-fill" /></template>
