<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr_vc52xd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dr_vc52xd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:television-off" /></template>
