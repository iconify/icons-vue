<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryb1uac7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryb1uac7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:workflow-pause" /></template>
