<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipfu2xicx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipfu2xicx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:unlocked-remove" /></template>
