<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcr65cb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcr65cb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:thumb-down-outline" /></template>
