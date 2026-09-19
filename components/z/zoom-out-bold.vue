<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-q298pwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-q298pwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:zoom-out-bold" /></template>
