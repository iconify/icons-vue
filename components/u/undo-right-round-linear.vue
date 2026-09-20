<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdldnkbyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdldnkbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:undo-right-round-linear" /></template>
