<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi9k0obgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mi9k0obgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:smart-power-strip" /></template>
