<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifu-l4bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifu-l4bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:roller-skate-off" /></template>
