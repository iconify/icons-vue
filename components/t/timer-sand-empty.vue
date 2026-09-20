<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckge42buj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckge42buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timer-sand-empty" /></template>
