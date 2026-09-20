<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf8y8l98m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uf8y8l98m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:settings-slider-desktop-horizontal-bold" /></template>
