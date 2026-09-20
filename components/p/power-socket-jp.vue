<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjj_rybhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjj_rybhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:power-socket-jp" /></template>
