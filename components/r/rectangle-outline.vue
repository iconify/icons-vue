<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccxqt5b2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccxqt5b2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rectangle-outline" /></template>
