<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0bixkb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0bixkb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:user" /></template>
