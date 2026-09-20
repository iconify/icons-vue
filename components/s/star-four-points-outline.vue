<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1gz_e17x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1gz_e17x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:star-four-points-outline" /></template>
