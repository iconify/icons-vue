<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n176kdbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n176kdbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timer-sand" /></template>
