<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukg75fbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukg75fbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:zap" /></template>
