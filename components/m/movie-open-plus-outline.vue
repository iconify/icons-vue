<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_bwmobsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_bwmobsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:movie-open-plus-outline" /></template>
