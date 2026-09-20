<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4e2-rves.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4e2-rves"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:planet-box-plus" /></template>
