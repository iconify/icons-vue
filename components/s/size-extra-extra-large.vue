<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c58st574x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c58st574x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:size-extra-extra-large" /></template>
