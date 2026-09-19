<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsk86rcsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsk86rcsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:panel-glass-side-door-locked" /></template>
