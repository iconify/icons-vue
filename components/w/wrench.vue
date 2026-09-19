<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oripv7bjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oripv7bjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:wrench" /></template>
