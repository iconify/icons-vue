<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y52du4bfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y52du4bfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:mosquitto" /></template>
