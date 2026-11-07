<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny2z_jjno.css';
import '../../css/m/m33dd1b0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ny2z_jjno"/><path class="m33dd1b0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:music-notes-bold" /></template>
