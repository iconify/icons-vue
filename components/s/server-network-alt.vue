<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_r8o4g5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_r8o4g5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:server-network-alt" /></template>
