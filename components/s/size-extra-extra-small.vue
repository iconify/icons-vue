<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p22l6fwcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p22l6fwcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:size-extra-extra-small" /></template>
