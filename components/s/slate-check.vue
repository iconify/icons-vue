<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n845l5bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n845l5bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:slate-check" /></template>
