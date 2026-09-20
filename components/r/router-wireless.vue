<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi7eyibmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi7eyibmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:router-wireless" /></template>
