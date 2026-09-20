<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7737sgbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7737sgbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:map-marker-fill" /></template>
