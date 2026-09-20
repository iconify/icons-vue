<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtb2k4dkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtb2k4dkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pail-outline" /></template>
