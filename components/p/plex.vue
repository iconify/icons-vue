<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opp5y0_jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opp5y0_jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:plex" /></template>
