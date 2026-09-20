<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5u27ab7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5u27ab7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:notifications" /></template>
