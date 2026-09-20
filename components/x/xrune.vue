<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8_9w5b9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8_9w5b9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:xrune" /></template>
