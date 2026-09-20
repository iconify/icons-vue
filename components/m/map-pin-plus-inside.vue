<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbc5s7bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbc5s7bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:map-pin-plus-inside" /></template>
