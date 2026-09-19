<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvy3c3b1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvy3c3b1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:transmission-virus-touch-finger" /></template>
