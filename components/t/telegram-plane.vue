<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssck75ytp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ssck75ytp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:telegram-plane" /></template>
