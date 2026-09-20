<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxvarnb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxvarnb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:office-building-remove-outline" /></template>
