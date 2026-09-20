<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do_r7ii-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="do_r7ii-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:panorama" /></template>
