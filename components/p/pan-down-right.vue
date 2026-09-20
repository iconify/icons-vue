<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmok20b9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmok20b9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pan-down-right" /></template>
