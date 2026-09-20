<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v75_03-ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v75_03-ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:surface-area" /></template>
