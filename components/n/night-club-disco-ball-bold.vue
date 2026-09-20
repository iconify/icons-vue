<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqkdsdbxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqkdsdbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:night-club-disco-ball-bold" /></template>
