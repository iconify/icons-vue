<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f47o1yuzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f47o1yuzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:panorama-fish-eye" /></template>
